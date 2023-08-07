# Programa-Control-de-giro-en-C-y-Proteus
This is a project that combines one code in C and one simulation with Proteus, I am using the PIC 18F4550, one LCD, and some buttons. 

*Write in Spanish

### Descripción del funcinoamiento del programa
El proyecto trata de una simulación del funcionamiento de un motor que puede cambiar el sentido de su giro, mandar una señal de velocidad del motor mediante dos botones y todo controlado con un PIC [18F4550]. _El programa no fue testeado en la realidad_

### Código. 
El código está programado en C, primero declaramos e incluimos las librerías necesarias como son la del PIC y la del LCD. Definimos algunos parámetros propios de las salidas y entradas del PIC.

Configuramos las funciones de los pulsos PWM. 

Generamos el **loop while** que le da el funcionamiento a todo el programa.

### Programa en Proteus
El diagrama en Proteus es intuitivo si seguimos el código. Lo elementos que usamos son los siguientes: 
* Transistor 2N2222A
* Diodos 4747A
* Fuente de alimentación de circuito de 24 V.
* Osciloscopio _Para ver comportamiento de las señales de salida del PIC_
* LCD con conexiones y Resistencia Variable
* Bonotes _para cambio de giro_
* **PIC 18F4550**

En el siguiente link podemos encontrar un video del funcionamiento del proyecto terminado. [Link del video en Youtube](https://youtu.be/pNNG_kJ-Nqg)



For more information please contact [^1] 🐺

[^1]: Iván Durán, ivan_hds11@hotmail.com



