# Interviewspracticejs/Algoritmos y estructura de datos para dummies

<p>Si alguna vez has intentado ingresar a leetcode como yo, y practicar para entrevistas tecnicas. Posiblemente te hayas encontrado mas de una vez que es un poco mas complejo de lo que imaginabas y eso probablemente se deba a que necesitas la teoria para poder resolver este tipo de problemas, pero en su mayoria esta explicado con conceptos que posiblemente viste pero no sabias que tenian ese nombre, encuentras toda la informacion por separado o solo practicaste en algun ejercicio en el cual no pusiste tanta atencion, para repasarlos he creado esta siguiente guia que incluye Algoritmos y estructuras de datos para dummies, como tu y como yo</p>

<p>Primero vamos a definir un Algoritmo como una serie de pasos para hacer algo. Es como le vamos a indicar a js, paso a paso que es lo que queremos que haga, es decir que las instrucciones deben estar bien definidas para que lo pueda interpretar y usualmente se utilizan para resolver un problema o realizar una tarea específica. Los algoritmos son fundamentales en la programación y se pueden aplicar a una amplia gama de problemas</p>


<p> A comparacion de una estructura de Datos: Una estructura de datos es una forma de organizar y almacenar cosas (datos) para que sea fácil encontrarlas y usarlas, la cual esta dividida de la siguiente manera: 
<h2>Estructuras lineales</h2>
<p>(Representada por arrays,linked lists y strings)</p>

<li>Arrays:</li>
<p> </p>
<img src="https://dc722jrlp2zu8.cloudfront.net/media/uploads/2019/10/04/cap1-estructuras1.png" width='250'>

<li>Linked list</li>
<p></p>
<img src="https://open4tech.com/wp-content/uploads/2019/03/array-linked-list.png" width='350'>

<li>Srings</li>
<p></p>
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/String_example.png" width='350'>



<h2>Y las estructuras no lineales</h2> 
<p> O como me gustan llamarlas, los que estan compuestos de circulos(nodos) y palitos(vertices)</p>

<li>Arboles(trees)</li>
<p>El primer tipo de estructura no lineal, son los arboles. Un arbol en las estructuras, es una manera de acomodar los datos por niveles, desde un nivel padre que va desde arriba, pasando por niveles mas bajos, que serian hijos y estos hijos a su vez pueden tener mas hijos y hermanos</p>
<p>Esta estructura de datos a su vez, esta dividida en 3</p>
<img src="https://media.geeksforgeeks.org/wp-content/uploads/20230111154258/typoes1.png" width='550'>

<li>Binary trees</li>
<p>Un árbol binario es una estructura de datos en la que cada padre(nodo) tiene a lo mucho dos hijos, que se denominan típicamente "hijo izquierdo" e "hijo derecho". Es similar a un árbol familiar con ramas, pero en este caso, cada nodo puede tener como máximo dos "ramas". O mas facil empezamos por niveles el primer nivel de hasta arriba va a tener una bola(nodo) mayor que sera llamado padre y de ahi ira hacia los niveles mas bajos, en este caso para los binary trees, cada bolita que venga del nivel de arriba para abajo solo puede tener otras dos bolitas/hijos o nodos maximo hacia abajo </p>
<li>Ternary tree</li>
<p>Un árbol ternario a diferencia de un arbol binario, permite cada padre(nodo) tener hasta tres hijos, 3 bolitas</p>
<li> N-ary tree</li>
<p>Un arbol N-ary no tiene ninguna restriccion para cada padre, puede tener un numero de hijos idefinidos.</p>
<p>Y a lo mejor te estas preguntando cuando usar cual</p>
<p>Por ejemplo, los Binary tree, son ideales para estructuras donde la eficiencia de búsqueda, inserción y eliminación es crucial, como en bases de datos y estructuras de indices</p>
<p>los ternary-trees:Son utiles para sistemas jerárquicos más complejos que los binarios, como ciertos sistemas de archivos.</p>
<p>Por ultimo nos n-ary trees son perfectos para estructuras con múltiples niveles de jerarquía y más de dos hijos por nodo, como menús de navegación y sistemas de archivos más complejos.</p>

<h2>Despues tenemos los Graficos(graphs)</h2>
<p>Tipos de Grafos en Estructuras de Datos
Un grafo es una estructura de datos no lineal compuesta por nodos y aristas.En cuanto a estructura es muy similar a un tree debido a su similitud de nodos y aristas. La diferencia a los trees, es que un arbol va de un nivel jerarquico, de arriba hacia abajo. A diferencia de este tipo de grafico, que no va por niveles. <p> La Cantidad total de de Tipos de Grafos
Existen entre 14 y 15 tipos de grafos. Sin embargo, el tipo de grafo más comúnmente usado es el grafo finito..</p>
<img src="https://www.simplilearn.com/ice9/free_resources_article_thumb/Graph%20Data%20Structure%20-%20Soni/FINITE-GRAPH-IN-GRAPHS-IN-DATA-STRUCTURE.png" width='500'>
<h3> Finite Graph</h3>
<p> Un grafo finito es un tipo de grafo que tiene un número limitado de nodos (vértices) y aristas (enlaces)</p>

<h3>Características</h3>
<p>Número Limitado de Nodos y Aristas: Como su nombre indica, un grafo finito tiene un número finito de nodos y aristas. Esto significa que puedes contar todos los nodos y todas las aristas del grafo.A diferencia de un tree o arbol, que va de arriba hacia abajo</p>

<li>Grafos Infinitos</li>

<li>Grafos Triviales</li>

<li>Grafos Simples</li>

<li>Grafos Múltiples</li>

<li>Grafos Nulos</li>

<li>Grafos Completos</li>

<li>Pseudo Grafos</li>

<li>Grafos Regulares</li>

<li>Grafos Etiquetados</li>

<li>Grafos Dirigidos</li>

<li>Subgrafos</li>

<li>Grafos Conectados o Desconectados</li>

<li>Grafos Cíclicos</li>
<p> si te interesa profundizar en todos, puedes ingresar al siguiente link</p>
<a href="https://www.simplilearn.com/tutorials/data-structure-tutorial/graphs-in-data-structure"> LINK AQUI</a>


 <p>Como los grafos finitos se utilizan en una amplia variedad de aplicaciones prácticas, vamos a enfocarnos mayormente en ellos desde la modelización de redes sociales hasta la optimización de rutas de transporte.<p>


<h3> Y adivina que, los Grafos Finitos, tambien estan divididos</h3>
<li>Su primer division son los Grafos no dirigidos:</li>
<p> Las aristas no tienen dirección, es decir, la relación entre dos nodos es bidireccional.</p>
 <img src="https://cdn-icons-png.flaticon.com/512/1430/1430894.png" width='300'>
<p> Por ejemplo la Representación de amistades en una red social, tu puedes entrar al perfil de tu amigo en una red social, y al tuyo</p>
 <img src="https://img.freepik.com/vector-premium/redes-sociales-conexion-personas_29937-5078.jpg" width='500'>

<li>>A diferencia de un Grafo Dirigido (Digrafo): Las aristas tienen una dirección específica, lo que significa que la relación entre dos nodos es unidireccional.</li>

<p>Por ejemplo el Grafo de una página web con enlaces dirigidos hacia otras páginas </p>

<li>Y por ultimo los Grafo Ponderado: Las aristas tienen un peso o costo asociado.</li>

<p>Por ejemplo cuando entras a la aplicacion de mapas, para encontrar la ruta más corta entre dos puntos en un mapa. Aqui el peso va a representar la distancia entre las ciudades.</p>

<p>Los graficos tambien estan divididos de la siguiente manera</p>




<p>Representación: Los grafos finitos se pueden representar mediante listas de adyacencia, matrices de adyacencia o incluso mediante otros métodos específicos dependiendo del contexto.<p>



  <img src="https://miro.medium.com/v2/resize:fit:1400/1*qTGoz5zljOdQEzlzf7N-Mw.png" width='500'>




- *Linear Data Structure Patterns:*
  1. *Two Pointers:*
     - Reduces time complexity to linear time \(O(n)\).
     - Two methods:
       - Same direction: used for scanning data in a single pass (e.g., fast and slow pointers to detect cycles or find middle elements).
       - Opposite directions: used for finding pairs (e.g., sum of two numbers in a sorted array).
  2. *Sliding Window:*
     - Refines two pointers to manage a window of elements dynamically.
     - Expands or contracts the window to meet specific conditions (e.g., longest substring without repeating characters).
     - Often combined with hashmaps.
  3. *Binary Search:*
     - Efficiently finds target in logarithmic time \(O(\log n)\).
     - Extends to lists with monotonic conditions, not just sorted numbers.
     - Example: finding the minimum in a rotated sorted array.

- *Nonlinear Data Structure Patterns:*
  4. *Breadth-First Search (BFS):*
     - Explores nodes level by level.
     - Uses a queue to keep track of visited nodes (ideal for level order traversal).
  5. *Depth-First Search (DFS):*
     - Dives deep into one path before exploring others.
     - Often uses recursion and is memory efficient for exploring all paths.
     - Example: counting islands in a grid.
  6. *Backtracking:*
     - Extension of DFS, explores all possible solutions.
     - Builds the solution dynamically by making decisions and backtracking on invalid paths.
     - Example: letter combinations of a phone number.

- *Heaps (Priority Queue):*
  7. *Heaps:*
     - Used for questions related to top K, K smallest/largest.
     - *Min Heap:* smallest value at the root.
     - *Max Heap:* largest value at the root.
     - Max Heap is used to find K smallest values, and vice versa for K largest.

- *Dynamic Programming (DP):*
  8. *Dynamic Programming:*
     - Optimizes solutions by breaking problems into overlapping subproblems.
     - Two approaches:
       - *Top-down:* recursive with memoization to store results.
       - *Bottom-up:* solves smaller subproblems iteratively using a table.
     - Too complex for this video but covered in-depth on their website.


<li>Sliding window</li>
<p>Este tipo de metodo te va a dar 2 clases de datos, un array y un numero entero. El metodo slide window consiste en imaginar que una ventana va moviendose a traves del array que te den y el numero entero va a indicar la cantidad de espacios o elementos del array que va a tomar dentro de la ventana imaginaria 

<p><img src=windowsliding.jpg,jpeg></p>

<li>Two pointers</li>
<p>Es una tecnica que se utilizar para resolver problemas en estructuras de datos lineales como arrays y listas enlazadas. </p>

<p>La técnica de dos punteros implica el uso de dos variables de puntero (o índice) que recorren la estructura de datos desde diferentes posiciones al mismo tiempo. Los punteros pueden moverse hacia adelante, hacia atrás o en cualquier dirección, dependiendo del problema que se está resolviendo.</p>

<p>Usos Comunes de Dos Punteros</p>
Búsqueda de Elementos: Encontrar pares en un array que sumen a un valor específico.

<p>Eliminar Duplicados: Remover duplicados de un array ordenado.<p>

Subcadenas y Subarreglos: Encontrar subcadenas con ciertas propiedades (como la longitud mínima).

<p>Ahora,un ejemplo a la resolucion a este tipo de problemas es el brute force approach, la segunda es el optimal approach</p>

<li>binary search</li>
<p>Binary search o búsqueda binaria es un algoritmo eficiente para encontrar un elemento en una lista ordenada. Funciona dividiendo repetidamente el espacio de búsqueda a la mitad hasta que se encuentra el elemento deseado o se determina que no está en la lista.</p>

<p>Concepto de Búsqueda Binaria
Requisito: La lista debe estar ordenada.</p>

<p>Debe tener una complejidad O(log n) indica que el número de operaciones necesarias para encontrar un elemento en una lista se reduce drásticamente cada vez que se duplica el tamaño de la lista.</p>

<p>En términos simples, si duplicamos el tamaño de la lista, solo necesitamos una operación adicional para encontrar un elemento.
Cómo Funciona
Inicialización: Se establecen dos punteros, inicio y fin, al principio y al final de la lista, respectivamente.</p>


<p>Cálculo del Punto Medio: Se calcula el índice medio de la lista.</p>


<p>Comparación:</p>

<p>Si el elemento en el índice medio es igual al elemento buscado, se ha encontrado el elemento.</p>

<p>Si el elemento buscado es menor que el elemento en el índice medio, se ajusta el puntero fin a medio - 1 (descartando la mitad derecha).</p>

<p>Si el elemento buscado es mayor, se ajusta el puntero inicio a medio + 1 (descartando la mitad izquierda).</p>

<li>breadth first search</li>
<li>backtracking</li>
<li>dynamic programming</li>
<li>Depth first search</li>
<li>Priority Queu</li>



<div> Brute force approach<li>

<p> </p>


<li>Hamiltonian Circuits</li>
<li>Sliding window</li>
<li>Sliding window</li>
<li>Sliding window</li>
<li>Sliding window</li>
<li>Sliding window</li>
<li>Sliding window</li>



Array / String
