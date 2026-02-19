O app mínimo Flutter tem uma função ``runapp()`` que roda uma Widget e faz ela se tornar a raiz da arvore de Widgets. Para os parametros de direção desta Widget já virem configurados, utilizamos a widget ``MaterialApp``. 

Geralmente as classes construídas irão herdar ou de ``StatelessWidget`` ou de ``StatefulWidget``. O que uma Widget faz é implementar uma função ``build()`` que descreve uma widget por outras Widgets.

``Row,Column`` - Widgets que implementam o flexbox
``Stack`` - Deixa posicionar as Widgets uma acima da outra 
``Positioned`` - mais ou menos o que o position faz no CSS(eu acho)
``Container`` - Cria um elemento retangular e decora com o ``BoxDecoration``

## Basico de uma aplicação Flutter

````
void main(){
	runApp(
	const NOMEDACLASSE(
		argumento: valor,
	),
	);
}
class NOMEDACLASSE extends StatelessWidget{
	const NOMEDACLASSE (this.argumento, super.key) // construtor da classe
	final Widget variavel; // Variavel do tipo Widget
	
	@override // Colocada antes de um método para indicar que esse que tá sendo criado está sobrescrevendo outro da classe Pai
	Widget build(BuildCOntext context){ // função build
		return Container( //cria um container na tela
		height: 10,
		padding: const EdgeInsets.symmetric(horizaontal: 8), //Cria deslocamentos constantes na direção dada
		decoration: BoxDecoration(color: Colors.blue[500]), // decora container
		child: Row(// Cria uma disposição horizontal em tela
			children: [ Lista de Widgets que serão usadas]
		)
		)
	}
	
}
````