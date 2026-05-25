# Preenchimento - Padding

As propriedades de preenchimento (padding) do CSS são usadas para gerar espaço ao redor do conteúdo de um elemento, dentro de quaisquer bordas definidas.

Com CSS, você tem controle total sobre o preenchimento (padding). Existem propriedades para definir o preenchimento de cada lado de um elemento (superior, direito, inferior e esquerdo), e uma propriedade abreviada para definir todas as propriedades de preenchimento em uma única declaração.

# O CSS possui propriedades para especificar o preenchimento (padding) de cada lado de um elemento:

* padding-top- define o espaçamento superior de um elemento
* padding-right- define o espaçamento correto de um elemento
* padding-bottom- define o espaçamento inferior de um elemento
* padding-left- define o espaçamento à esquerda de um elemento

# Todas as propriedades de preenchimento podem ter os seguintes valores:

comprimento - especifica um espaçamento em px, pt, cm, etc.
% - especifica um espaçamento em % da largura do elemento que o contém.
`inherit` - especifica que o preenchimento deve ser herdado do elemento pai.

# Preenchimento - Propriedade abreviada

Para encurtar o código, é possível especificar todas as propriedades de preenchimento em uma única declaração.

A padding propriedade é uma abreviação para as seguintes propriedades de preenchimento individuais:

padding-top
padding-right
padding-bottom
padding-left
Funciona assim:

Se a padding propriedade tiver quatro valores:

preenchimento: 25px 50px 75px 100px;
O espaçamento superior é de 25px.
O espaçamento à direita é de 50px.
O espaçamento inferior é de 75px.
O espaçamento à esquerda é de 100px.

Se a padding propriedade tiver três valores:

preenchimento: 25px 50px 75px;
O espaçamento superior é de 25px.
Os espaçamentos laterais direito e esquerdo são de 50px.
O espaçamento inferior é de 75px.

Se a padding propriedade tiver dois valores:

preenchimento: 25px 50px;
As margens superior e inferior são de 25px.
Os espaçamentos laterais direito e esquerdo são de 50px.

Se a padding propriedade tiver um único valor:

preenchimento: 25px;
Todos os quatro preenchimentos têm 25px.

# Preenchimento e Largura do Elemento

A width propriedade CSS especifica a largura da área de conteúdo do elemento

A área de conteúdo é a porção delimitada pelo preenchimento (padding), borda (border) e margem (margin) de um elemento ( o modelo de caixa ).

Se um elemento tiver uma largura especificada, o preenchimento adicionado a esse elemento será somado à largura total do elemento.

# Padding e Box-sizing

Essa propriedade box-sizing define como a largura e a altura de um elemento são calculadas: se devem incluir preenchimento e bordas, ou não.

A propriedade box-sizing pode ter os seguintes valores:

* content-box: Este é o valor padrão. As propriedades de largura e altura incluem apenas o conteúdo (bordas e preenchimento não estão incluídos).

* border-box: As propriedades de largura e altura incluem conteúdo, preenchimento e borda.