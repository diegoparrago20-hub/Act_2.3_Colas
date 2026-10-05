# Act_2.3_Colas

Este proyecto consiste en el desarrollo de una estructura de datos tipo Cola (FIFO), utilizando nodos en Java. Cuenta con una interfaz gráfica desarrollada en Java Swing mediante NetBeans, que permite visualizar y realizar las operaciones principales de una cola.

# Equipo #2

CONTRERAS RODRIGUEZ JANIS ISABEL

LIRA DOMINGUEZ BRYANT

PARRA GONZALEZ DIEGO ALBERTO

# Objetivo

Implementar y comprender el funcionamiento de una estructura de datos Cola basada en nodos, aplicando el principio FIFO (First In, First Out), donde el primer elemento en entrar es el primero en salir.

# Tecnologías utilizadas

Java, Java Swing, Apache NetBeans, Git y GitHub.

# Operaciones de la cola

Encolar (Enqueue): Agrega un nuevo elemento al final de la cola.

Desencolar (Dequeue): Elimina y devuelve el elemento que se encuentra al frente de la cola.

Consultar Frente (Front o Peek): Muestra el elemento que está al frente sin eliminarlo.

Está Vacía (IsEmpty): Comprueba si la cola no contiene elementos.

Tamaño (Size): Muestra la cantidad de elementos almacenados.

Vaciar Cola (Clear): Elimina todos los elementos de la cola.

# Estructura del proyecto

El proyecto se organiza en tres partes principales:

Modelo de dominio: Representa los elementos que se almacenarán en la cola.

Nodo: Almacena un elemento y una referencia al siguiente nodo.

Cola: Administra los nodos mediante referencias al frente y al final, y contiene las operaciones correspondientes.

Interfaz gráfica: Permite interactuar con la cola mediante botones y visualizar su contenido.

# Interfaz gráfica

La interfaz fue diseñada en Java Swing mediante NetBeans y contiene:

Campos para ingresar el nombre, ID y tipo del elemento.

Botones para ejecutar las operaciones de la cola.

Un área de visualización para mostrar los elementos almacenados desde el frente hasta el final.

Indicadores para mostrar el elemento que se encuentra al frente y el tamaño actual de la cola.

# Funcionamiento

La cola trabaja bajo el principio FIFO. Los elementos se agregan al final y se eliminan desde el frente, manteniendo el orden de llegada. Su almacenamiento se realiza mediante nodos enlazados dinámicamente, permitiendo administrar los elementos sin utilizar arreglos ni las colecciones prediseñadas de Java.
