# Estilizando elementos :small_blue_diamond:

## Padding e Margin
Os exemplos seguintes são tanto para **margin** como para **padding**
1. Forma :arrow_right: Dessa forma todos os lados receberão o mesmo valor
- *margin*: 10px; 

2. Forma :arrow_right: Em sentido horário as cada lado recebe um valor diferente (TOP, RIGHT, DOWN e LEFT).
- *margin*: 15px 10px 5px 0; 

3. Forma :arrow_right: Cada *margin* recebe individualmente um valor de acordo com a sua posição
- *margin-top*: 15px;
- *margin-right*: 10px;
- *margin-down*: 5px;
- *margin-left*: 0px;

## Background
Possui várias propriedades além do *color*. Pode ser vista melhor na documentação [MDN](https://developer.mozilla.org/pt-BR/docs/Web/CSS/background)

1. Forma :arrow_right: Inserindo o nome da cor em inglês
- background-color: #red;
2. Forma :arrow_right: Inserindo o código hexadecimal
- background-color: #FF0000;
3. Forma :arrow_right: Inserindo o código RGB
- background-color: rgb(255 0 0);

## Border
Pode conter 3 valores: a largura, a cor e o estilo

- border: 1px red solid;
- - Primeiro valor :arrow_right: Espessura da borda
- - Segundo valor :arrow_right: Cor da borda
- - Terceiro valor :arrow_right: Estilo da borda
- - - solid :arrow_right: Simples e reta
- - - dotted :arrow_right: Círculo com um pequeno espaçamento central entre ela
- - - solid :arrow_right: Linha tracejada

A mesma forma de fazer a estilização acima porém com códigos específicos
- border-width :arrow_right: Largura
- border-color :arrow_right: Cor
- border-style :arrow_right: Estilo

- border-radius: 10px; :arrow_right: Permite arredondar os cantos de um elemento. Podemos usar várias unidades, mas as mais comuns são os pixels e a porcentagem.

[:leftwards_arrow_with_hook: MENU](README.md)