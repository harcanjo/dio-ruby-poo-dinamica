# Dinâmica de Mercado com POO em Ruby

## Objetivo Geral

Criar um programa na linguagem Ruby utilizando as ferramentas aprendidas em POO.

## Desafio

Criar um código em três arquivos que "conversem" entre si como aprendido nas aulas. Você simulará o ato de escolher e comprar um produto em um mercado.

## Instruções
1 - No arquivo produto.rb, crie uma classe chamada Produto com os atributos: nome e preco. 
2 - No arquivo mercado.rb crie uma classe chamada Mercado que ao ser inicializada recebe como atributo um objeto da classe Produto. 
3 - Dentro da classe, crie um método chamado comprar que imprime a seguinte frase “Você comprou o produto #{@produto.nome} no valor de #{@produto.preco}” 
4 - No arquivo app.rb crie uma instância da classe Produto e adicione valores aos atributos nome e preco. Depois, inicie uma instância da classe Mercado passando um objeto produto como atributo e para finalizar execute o método comprar.