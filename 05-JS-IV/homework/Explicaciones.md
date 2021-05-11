Objeto

	Es un conjunto de cajitas parecido a los arreglos o matrices.
	La diferencia entre estos es que siendo un objeto se pueden describir mas caracteristicas de una cosa.
	El arreglo trae su indice definido como numeros y con un solo valor, en los objetos puedes definir su nombre y su valor.
	ejemplo:

	arreglo
	 var carro = [carro1, carro2, ...];

	objeto
	 var carro = {
	  marca: toyota,
	  color: rojo,
	  placa: ada749
	}

propiedades
	
	Son como se llaman los indeces en los objetos.

	Mientras que en los arreglos se llama indice y es entero, en los objetos pueden ser string o entero.

metodos
	
	Se llama así a una funcion que se encuentra dentro de un objeto.

	ejemplo:
	var carro = {
	  marca: toyota,
	  color: rojo,
	  placa: ada749,
	  saludar : function(){// metodo
	  	return "Hola";
	  }
	}

bucle for in
	
	El ciclo for normal recorre arreglos utlizando sus indices enteros.

	Es un ciclo for alterado un poco ya que este recorre objetos ya que sus propiedades no siempre son enteros.

Notación de puntos vs notación de corchetes
	
	La notacion de puntos es mas literal ya solo te va a devolver algo cunado estas digitando directamente el nombre de una propiedad. Pero es la mas utilizada.

	La notacion de corchetes se utiliza cuando se quiere utilizar el contenido de una variable ya que con la notacion de puntos no se ´puede ultilizar una variable.