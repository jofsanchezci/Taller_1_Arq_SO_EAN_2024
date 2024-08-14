## Workshop 1. Part One: Numbering Systems and Arithmetic Operations

**Objective**: To evaluate and reinforce knowledge in conversions between number systems, use of BCD and Gray codes, understanding of data structure (byte, nibble, word), and basic arithmetic operations with binary numbers, including two's complement.

### Decimal to Binary, Octal and Hexadecimal Conversion
- Implements a Python function that converts a decimal number to its binary, octal, and hexadecimal representations.

### Binary to Decimal Conversion
- Write a Python function that converts a binary number (as a string) to its decimal equivalent.

### Hexadecimal to Decimal and Binary Conversion
- Implements a function that converts a hexadecimal number (as a string) to its decimal and binary equivalent.

### Conversion to BCD Code
- Implements a function that converts a decimal number to its BCD code representation.

### Binary to Gray Code Conversion
- Write a Python function that converts a binary number to Gray Code.

### Data Structure Identification
- Implement a Python function that identifies whether a binary string corresponds to a nibble, byte, or word.

### Operation with Nibbles
- Implement a function that performs the binary addition of two nibbles and returns the result as a byte.

### Character to ASCII and EBCDIC Code Conversion
- Implement functions that convert one character to its ASCII code and another to its EBCDIC equivalent (you can use a fixed conversion table for EBCDIC).

### Sum of Binary Numbers
- Write a Python function that adds two binary numbers.

### Subtract with Two's Complement:

- Implement a function subtracting two binary numbers using the two's complement method.



## Taller 1. Segunda Parte: Sistemas Numéricos en Diferentes Bases

Imagina que trabajas en una empresa de tecnología que ha desarrollado un nuevo sistema de almacenamiento que utiliza una base numérica inusual: la **base 13**. Tu tarea es desarrollar un software que pueda convertir números entre la base 10 (decimal) y esta nueva base 13, además de realizar algunas conversiones adicionales entre otras bases.

### 1. Identificación de Dígitos en Base 13 (1 punto)
- Antes de realizar las conversiones, es importante entender cómo se representan los números en base 13. En este sistema, los dígitos van del 0 al 9 y se agregan tres símbolos adicionales para representar los valores 10, 11, y 12. Estos pueden representarse como A, B, y C respectivamente.
**Pregunta**: ¿Cuáles son los dígitos válidos en un sistema de base 13? Describe cómo representarías los números 10, 11, y 12 en este sistema.

### 2. Conversión de Decimal a Base 13 (2 puntos):

- Implementa una función en Python que convierta un número en base 10 a su equivalente en base 13.
- **Ejercicio**: Convierte el número decimal 255 a base 13. ¿Cuál es la representación de este número en base 13?

### 3. Conversión de Base 13 a Decimal (2 puntos)
- Ahora, implementa una función que convierta un número en base 13 a su equivalente en base 10.
- **Ejercicio**: Convierte el número 1A2 en base 13 a decimal. ¿Cuál es el valor en base 10?

### Conversión de Base 13 a Binario (2 puntos):

- Escribe una función que convierta un número en base 13 a su equivalente en binario, pasando primero por la conversión a base 10.
- **Ejercicio**: Convierte el número B3 de base 13 a binario.


### Conversión de Binario a Base 13 (2 puntos):
- Escribe una función que convierta un número binario a su equivalente en base 13, pasando primero por la conversión a base 10.
- **Ejercicio**: Convierte el número binario 1101011 a base 13.

### Conversión de Base 13 a Hexadecimal (1 punto):

- Implementa una función que convierta un número en base 13 a hexadecimal, utilizando la base 10 como paso intermedio.
- **Ejercicio**: Convierte el número 9C de base 13 a hexadecimal.

### Aplicación en el Almacenamiento de Datos (2 puntos):

- Imagina que en tu empresa se decide almacenar ciertos identificadores utilizando la base 13 debido a su eficiencia. Si un identificador en base 10 es 3456, ¿cómo se vería este identificador en base 13? 
- Además, convierte este identificador de base 13 a binario para mostrar cómo se almacenaría en un sistema digital.

-**Ejercicio**: Realiza las conversiones y explica por qué podría ser ventajoso utilizar bases numéricas no convencionales en ciertos sistemas.