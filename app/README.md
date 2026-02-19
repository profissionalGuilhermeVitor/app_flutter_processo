# app

A new Flutter project.

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://docs.flutter.dev/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://docs.flutter.dev/cookbook)

For help getting started with Flutter development, view the
[online documentation](https://docs.flutter.dev/), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

O app mínimo Flutter tem uma função ``runapp()`` que roda uma Widget e faz ela se tornar a raiz da arvore de Widgets. Para os parametros de direção desta Widget já virem configurados, utilizamos a widget ``MaterialApp``. 

Geralmente as classes construídas irão herdar ou de ``StatelessWidget`` ou de ``StatefulWidget``. O que uma Widget faz é implementar uma função ``build()`` que descreve uma widget por outras Widgets.

``Row,Column`` - Widgets que implementam o flexbox
``Stack`` - Deixa posicionar as Widgets uma acima da outra 
``Positioned`` - mais ou menos o que o position faz no CSS(eu acho)
``Container`` - Cria um elemento retangular e decora com o ``BoxDecoration``
