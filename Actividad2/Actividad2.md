# *Datos Digitales* 🖥️

### Ejercico 1 🤖



1. Escribe un párrafo explicando, en tus propias palabras, cómo se representan los datos en una computadora. Por ejemplo, ¿cómo se ingresan números, letras, imágenes a una computadora?

R/ los datos se representan mediante un sistema binario (usando los digitos 0 y 1, osea Bits). 

#### Letras 
Se representan mediante codigos numericos como el sistema ASCII.
 
#### Numeros 
Tambien se codifican en binario, usando secuencias de 0 y 1 para reflejar su valor.

#### Imagenes 
 Se descomponen en pixeles, cada pixel se representapor un conjunto de bits, lo cual define las caracteristicas de la imagen.

2. Luego de realizar el ejercicio 1, escribe tus conclusiones acerca de la pregunta planteada en la Figura 2. ¿Cuántos estados diferentes pueden ser representados por N variables binarias?

R/ Cada variable binaria puede tener dos valores posibles: 0 o 1. Si se tienen N variables binarias, cada una puede estar en dos estados de manera independiente de las otras, por lo que el número total de combinaciones posibles que se pueden representar con N variables binaria es= 

$2^N$

**Se deriva con la regla de la muldiplicacion:**
como cada variable tiene 2 opciones y hay N variables, el número total de combinaciones es 2 multiplicado por sí mismo N veces, lo que da como:

$2^N$

3. ¿Cuáles son las unidades de almacenamiento de datos que se utilizan en computación? Crea una tabla donde muestres estas unidades con sus prefijos. En este caso me refiero a KiloByte, MegaByte, etc. 

R/ 

| Unidad | Simbolo | Prefijo | Cantidad en bytes |
|--------------|--------------| ------------ |--------------|
| Byte | B | -| 1 byte |
| Kilobyte | KB | Kilo | 1,024 bytes |
| Megabyte | MB | Mega | 1,024 KB (1,048,576 bytes) |
| Gigabyte | GB | Giga | 1,024 MB (1,073,741,824 bytes) |
| Terabyte | TB | Tera | 1,024 GB (1,099,511,627,776 bytes) |
| Petabyte | PB | Peta | 1,024 TB (1,125,899,906,842,624 bytes) |
| Exabyte | EB | Exa | 1,024 PB (1,152,921,504,606,846,976 bytes) |
| Zettabyte | ZB | Zetta | 1,024 EB (1,180,591,620,717,411,303,424 bytes)|
| Yottabyte | YB | Yotta | 1,024 ZB (1,208,925,819,614,629,174,706,176 bytes) |


 4. Incluye un pequeño resumen, de un par de renglones, donde menciones la importancia del trabajo de George Bool en este tópico.

 R/ El trabajo de George Boole nos permite ahora a permite representar datos y operaciones lógicas mediante valores binarios (0 y 1), lo que se convierte en la base para el almacenamiento, procesamiento y transmisión de información en computador.   
  ‎ 

 ![George](../images/28.png) 
   ‎ 
 # Tipos De Datos 🌌
### Ejercicio 2

Investiga los diferentes tipos de datos que se utilizan en varios lenguajes de programación (por ejemplo, C, Java, Python). Ten en cuenta cómo cada lenguaje define los números enteros, los decimales (o flotantes), las letras del alfabeto, las cadenas de texto, valores booleanos, entre otros. Investiga qué nombres se asignan y qué abreviaciones se utilizan en cada lenguaje.


| Datos | Python | C | Java | C++ |
|--------------|--------------|-------|---|---|
| Void | | x|x|
| Char | | x||x|
| int  |  |x | x|x|
| float|  x| x|x|x|
| str | x|
| Bool|x ||x|x|
| Long|||x|x|
| complex| x|||
| Double| | x|x|x|

**Python**
 
 |Dato|Tamaño|
 |---|---|
 |int|
 |float|
 |str|
 |Bool|
 |complex|

 **C**

 |Dato|Tamaño|
 |---|---|
|void|2byte|
|char|1byte|
|int|2byte|
|float|4bytes|
|double|8bytes|

 **Java**

 |Dato|Tamaño|
 |---|---|
 |void|
 |int|
 |float|
 |Bool|
 |Long|
 |double|

 **C++**

 |Dato|Tamaño|
 |---|---|
 |char|1byte|
 |int|4bytes|
 |float|4bytes|
 |bool|1byte|
 |long|8 bytes|
 |double|8bytes|

 ## Ejercicios 🧠

 1. Ahora es tu turno de intentar usar el método. Te voy a proponer varios números binarios y tú vas a convertirlos a decimales utilizando la tabla 3. Recuerda que el subíndice 2 significa que el número es binario (base 2)

 1. $1010101010_2$
Usamos la tabla para ver qué valores corresponden a cada posición:

1. $1010101010_2$
Usamos la tabla para ver qué valores corresponden a cada posición:



1.1010101010 2 =256+64+16+4+1=341 10

2.​11111 2 =16+8+4+2+1= 31 10
​

3.10000000 2 = 128 = 128 10

4.100100100 2 = 256 + 32 + 4 = 292 10



2. Vas a convertir los siguientes  números decimales a binarios. Recuerda que el subíndice 10 significa que el número es decimal

### - $127_{10}$ a binario

127 ÷ 2 = 63 (resto 1)

63 ÷ 2 = 31 (resto 1)

31 ÷ 2 = 15 (resto 1)

15 ÷ 2 = 7 (resto 1)

7 ÷ 2 = 3 (resto 1)

3 ÷ 2 = 1 (resto 1)

1 ÷ 2 = 0 (resto 1)

$127_{10}$ = $1111111_{10}$

### - $246_{10}$ a binario


246 ÷ 2 = 123 (resto 0)

123 ÷ 2 = 61 (resto 1)

61 ÷ 2 = 30 (resto 1)

30 ÷ 2 = 15 (resto 0)

15 ÷ 2 = 7 (resto 1)

7 ÷ 2 = 3 (resto 1)

3 ÷ 2 = 1 (resto 1)

1 ÷ 2 = 0 (resto 1)

$246_{10}$ = $11110110_{2}$
​
 

### - $1025_{10}$ a binario
​
1025 ÷ 2 = 512 (resto 1)

512 ÷ 2 = 256 (resto 0)

256 ÷ 2 = 128 (resto 0)

128 ÷ 2 = 64 (resto 0)

64 ÷ 2 = 32 (resto 0)

32 ÷ 2 = 16 (resto 0)

16 ÷ 2 = 8 (resto 0)

8 ÷ 2 = 4 (resto 0)

4 ÷ 2 = 2 (resto 0)

2 ÷ 2 = 1 (resto 0)

1 ÷ 2 = 0 (resto 1)

$354_{10}$ = $101100010_{2}$
