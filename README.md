# Interviewspracticejs

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
<img src="https://open4tech.com/wp-content/uploads/2019/03/array-linked-list.png" width='250'>

<li>Srings</li>





<h2>Y las estructuras no lineales</h2> 
<p>representados por arboles(trees) y graficos(graphs)<p>


Linear structures:* arrays, linked lists, strings.
    - *Nonlinear structures:* trees, graphs.
  - Focus on pre-built code templates for these patterns.

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
