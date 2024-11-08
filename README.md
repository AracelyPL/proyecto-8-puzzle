Alumna: Vanessa Aracely Pérez López

Materia: Inteligencia Artificial

Poryecto: 8-puzzle

Descripcion del proyecto:

Este proyecto se basa en el juego de puzzle, en el cual, mediante distintos metodos se debe hayar una solucion.

partiendo de un estado inicial = [[1, 2, 3], [4, 5, 0], [6, 7, 8]] para llegar al estado final = [[1, 2, 3], [4, 5, 6], [7, 8, 0]]

Los metodos que se deben aplicar para la resolucion del juego son:

1. Busqueda en lo profundo (Depth-First Search (DFS)) 

2. Busqueda en lo ancho (Breadth-First Search (BFS)) 

3. A*

4. Greedy

Contando con un boton de reinicio, ademas de mostrar el nombre del metodo que se esta utilizando y el número de pasos que recorre para hayar la solución.

Para esta aplicacion se hicieron 3 clases llamadas, intento.py (vista), metodos.py (modelo) y puzzle.py (controlador) estas clases representando el modelo vista controlador.


Para ejecutar el codigo, primero abrimos la terminal cmd, luego utilizando el comando "cd" agregamos la dirección de la carpeta en la que tenemos guardado las clases del proyecto.
una vez en la dirección de esa carpeta escribimos el siguiente comando: "python intento.py" para ejecutar el codigo, apareciendo de este modo la vista (interfaz) del proyecto.

![image](https://github.com/user-attachments/assets/2704a34c-2819-442b-aa70-2c00a6eb5d91)

Ahi, realizamos las pruebas, que son presionar cada uno de los botones para resolver el juego y de tal modo ordenas los números de menor a mayor.

El primer metodo que se ejecuto fue el de busqueda en lo ancho:

![image](https://github.com/user-attachments/assets/68e8d0c3-37db-4519-8be6-8bf0525244df)

Mostrando el nombre del metodo y los la cantidad de pasos que tardo en resolver el juego.


Otro ejemplo, es el metodo A*:

![image](https://github.com/user-attachments/assets/152eac65-5313-45a5-9d18-7c90babb5bda)


Y por ultimo el metodo Greedy:

![image](https://github.com/user-attachments/assets/e30ab0a0-6fdd-40a2-b2cf-e9d5028114ab)

En este ultimo podemos observar que el número de pasos aumento a 30, sin embargo, se pudo resolver el juego.










