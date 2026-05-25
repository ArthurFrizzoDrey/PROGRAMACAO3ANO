# Margens - Margin

As propriedades de margem CSS são usadas para criar espaço ao redor dos elementos, fora de quaisquer bordas definidas.

As margens definem a distância entre a borda de um elemento e os elementos circundantes.

Com CSS, você tem controle total sobre as margens. O CSS possui propriedades para definir a margem de cada lado individual de um elemento (superior, direita, inferior e esquerda), além de uma propriedade abreviada para definir todas as margens em uma única declaração.

# Margem - Propriedades Individuais

# O CSS possui propriedades para especificar a margem de cada lado de um elemento:

* margin-top: define a margem superior de um elemento
* margin-right: define a margem direita de um elemento
* margin-bottom: define a margem inferior de um elemento
* margin-left: define a margem esquerda de um elemento

# Todas as propriedades de margem podem ter os seguintes valores:

automático - o navegador calcula a margem
comprimento - especifica uma margem em px, pt, cm, etc.
% - especifica uma margem em % da largura do elemento que o contém.
`inherit` - especifica que a margem deve ser herdada do elemento pai.

# Margem - Propriedade abreviada

Para encurtar o código, é possível especificar todas as propriedades de margem em uma única declaração.

A margin propriedade é uma abreviação para as seguintes propriedades de margem individuais:

margin-top
margin-right
margin-bottom
margin-left

Se a margin propriedade tiver quatro valores:

margem: 25px 50px 75px 100px;
A margem superior é de 25px.
A margem direita é de 50px.
A margem inferior é de 75px.
A margem esquerda é de 100px.

Se a margin propriedade tiver três valores:

margem: 25px 50px 75px;
A margem superior é de 25px.
As margens direita e esquerda são de 50px.
A margem inferior é de 75px.

Se a margin propriedade tiver dois valores:

margem: 25px 50px;
As margens superior e inferior são de 25px.
As margens direita e esquerda são de 50px.

Se a margin propriedade tiver um único valor:

margem: 25px;
Todas as quatro margens têm 25px.


# Margem - auto

Você pode definir a margin propriedade para autocentralizar horizontalmente o elemento dentro do seu contêiner.

O elemento ocupará então a largura especificada, e o espaço restante será dividido igualmente entre as margens esquerda e direita.

# Margem - inherit

Você pode definir a margin propriedade para inheritque a margem seja herdada do elemento pai.