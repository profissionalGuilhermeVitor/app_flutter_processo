O app mínimo Flutter tem uma função ``runapp()`` que roda uma Widget e faz ela se tornar a raiz da arvore de Widgets. Para os parametros de direção desta Widget já virem configurados, utilizamos a widget ``MaterialApp``. 

Geralmente as classes construídas irão herdar ou de ``StatelessWidget`` ou de ``StatefulWidget``. O que uma Widget faz é implementar uma função ``build()`` que descreve uma widget por outras Widgets.

``Row,Column`` - Widgets que implementam o flexbox
``Stack`` - Deixa posicionar as Widgets uma acima da outra 
``Positioned`` - mais ou menos o que o position faz no CSS(eu acho)
``Container`` - Cria um elemento retangular e decora com o ``BoxDecoration``
