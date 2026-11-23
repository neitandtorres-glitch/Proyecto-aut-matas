&#x20;Desarrollado por Neitan Daniel Torres Vásquez

# ***Manual de Simulador de la Jerarquía de Chomsky***

&#x09;				         Ultima edición

&#x20;  

###### **1. Descripción general.**



Es una aplicación con interfaz gráfica interactiva para simular y validar el comportamiento de los cuatro niveles de la Jerarquía de Chomsky (Nivel 3, Nivel 2, Nivel 1 y Nivel 0)



###### **2. Cómo ejecutar el simulador de la Jerarquía de Chomsky.**



&#x09;2.1 Descarga o clona este repositorio en tu computador.

&#x09;2.2 Asegúrate de tener el archivo "index.html" en la carpeta del proyecto.

&#x09;2.3 Haz doble clic sobre "index.html" para abrirlo en tu navegador web (Chrome, Edge, Firefox, etc.).

&#x20; 	    Advertencia: No requiere instalar librerías, compiladores ni servidor adicional.

&#x09;2.4 En el menú principal, selecciona el módulo que desees probar (Nivel 3, Nivel 2, Nivel 1 o Nivel 0) y usa los controles paso a paso, reproducción 	  	    automática o evaluación inmediata.

###### 

###### **3. Ejemplos de cadenas de prueba por nivel.**



Nivel 3 **—** Lenguaje Regular (Autómata Finito Determinista):

&#x09;- Propósito: Reconocimiento de cadenas símbolo a símbolo mostrando los estados del autómata y el estado actual.

&#x09;- Cadenas de ejemplo: "abb", "abba", "aabb", "b".



Nivel 2 **—** Lenguaje Libre de Contexto (Memoria LIFO / Pila):

&#x09;- Propósito: Reconocimiento de lenguajes con pila mostrando en tiempo real los cambios en la pila mientras se consume la entrada.

&#x09;- Cadenas de ejemplo: "aabb", "aaabbb", "ab", "aab".



Nivel 1 **—** Lenguaje Sensible al Contexto (Cinta Acotada):

&#x09;- Propósito: Reconocimiento con memoria acotada a la longitud de la entrada, delimitadores de frontera y movimiento bidireccional del cabezal.

&#x09;- Cadenas de ejemplo: "aabbcc", "aaabbbccc", "abc", "aabb".



Nivel 0 **—** Recursivamente Enumerable (Máquina de Turing):

&#x09;- Propósito: Ejecución para aceptación de cadenas o funciones aritméticas sencillas con cinta extendible, alfabeto de cinta, cabezal de lectura/escritura 	             y estado activo.

&#x09;- Cadenas / entradas de ejemplo: "0011", "101", "11+11" (o las opciones pre cargadas en el módulo de Nivel 0).







