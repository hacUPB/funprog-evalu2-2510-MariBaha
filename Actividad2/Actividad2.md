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