
#  Bases de Datos NoSQL

## Origen

El origen de las bases de datos no relacionales se remonta a finales de la década de los 90, cuando Carlos Strozzi lo usó por primera vez para referirse a su base de código abierto la cual no ofrecía un lenguaje SQL. 

A pesar de esto, el término no adquirió popularidad hasta 2009 gracias a un empleado de la empresa Rackspace quien lo empleó para descubrir y distribuir una nueva generación de bases no relacionales.

## Nivel de Adopción

El motivo principal de que aumentara su empleabilidad fue ocasionado por la llegada del Big Data, con la necesidad de sistemas capaces de manejar cantidades grandes de información no estructurada (mensajes en redes sociales, imágenes, datos, etc). El sistema de las bases NoSQL resultó ser muy eficiente para gestionar esta clase de datos al ser más eficiente que las estructuras rígidas de las bases relacionales. 

## Ventajas

1. Son más flexibles para elaborar esquemas de información
2. Fácilmente escalables horizontalmente, utilizadas para trabajar con grandes volúmenes de información
3. Su rendimiento es alto debido a que se han preparado para trabajar con patrones y modelos de datos específicos
4. Gracias a sus API exclusivas y la proporción de modelos creados para gestionar los distintos tipos de datos se han convertido en un sistema de almacenamiento muy funcional

## Inconvenientes

1. Son incompatibles con las consultas realizadas en lenguaje SQL
2. No tienen un sistema estandarizado
3. No poseen el soporte que puede proporcionar una empresa comercial al ser de código abierto
4. Suelen tener problemas de compatibilidad dado que no comparten un estándar

## Descripción del Funcionamiento

Las bases de datos no relacionales se emplean para almacenar datos no estructurados, de los que no se tiene ninguna información predefinida. Sin embargo, también se pueden utilizar para el almacenamiento y gestión de datos estructurados. En el ejemplo de una base de datos en la que se almacenarán DVDs de películas, estos podrían almacenarse en cuanto al título, fecha de estreno, género y director. 

En el caso de las bases de datos no relacionales, cada registro de una película se almacena como un único documento JSON. Todas se almacenan en un solo documento, es decir, que este almacenamiento nos ayuda a tener mayor escalabilidad horizontal y un desarrollo más intuitivo.

## Tipos

### Clave-valor

En este tipo de bases de datos no relacionales almacena la información en pares formados por una clave y su correspondiente valor. La clave actúa como un identificador único, mientras que el valor contiene los datos asociados. Este modelo es ideal para aplicaciones que requieren rapidez y escalabilidad, como en el caso de videojuegos, dispositivos conectados al Internet de las Cosas (IoT) o sistemas de caché.

### Documentos

En este modelo, los datos se almacenan en forma de documentos, generalmente en formato JSON, lo que ofrece flexibilidad y permite manejar estructuras jerárquicas y semiestructuradas. Esto facilita a los desarrolladores el proceso de almacenamiento, gestión y consulta sin tener que ceñirse a un esquema rígido. Es comúnmente empleado en sistemas de gestión de contenidos y en la administración de perfiles de usuarios.

### Gráficos

Las bases de datos de gráficos están diseñadas para gestionar datos que tienen relaciones complejas. Las entidades se representan mediante nodos y las relaciones entre ellas se modelan con aristas. Este enfoque resulta especialmente útil en redes sociales, motores de recomendación y sistemas dedicados a la detección y prevención de fraudes.

### En memoria

Las bases de datos en memoria están pensadas para ofrecer respuestas extremadamente rápidas, con tiempos de acceso medidos en milisegundos. Son capaces de manejar grandes volúmenes de tráfico, lo que las convierte en una solución ideal para aplicaciones que requieren procesamiento en tiempo real, como clasificaciones en videojuegos o herramientas de análisis de datos en tiempo real.

## Usos

Las bases de datos NoSQL sobresalen en casos donde es necesario manejar una gran cantidad de usuarios distribuidos globalmente, brindando experiencias altamente personalizadas. Este tipo de aplicaciones interactivas se benefician de la flexibilidad y agilidad que ofrecen las bases de datos NoSQL.

Estas bases de datos priorizan la alta disponibilidad, proporcionan un rendimiento constante, escalan horizontalmente de manera rápida sin interrupciones y son capaces de gestionar grandes volúmenes de datos variados.

Estas características hacen que las bases de datos NoSQL sean ideales para aplicaciones que requieren alta escalabilidad, confiabilidad y disponibilidad continua.

Entre los casos de uso más comunes de NoSQL se encuentran:

- Aplicaciones web, IoT y móviles
- Aplicaciones web en tiempo real
- Personalización, recomendaciones y experiencias en tiempo real para los usuarios
- Gestión de inventarios y catálogos
- Detección de fraudes y autenticación de identidad
- Tecnología publicitaria

Illán Y Samuel.
## Ficheros
### Origen. ¿Cuándo surgió? ¿Cómo se popularizó?
Los primeros ficheros informáticos fueron en tarjeta perforada (ya la máquina de Hollerith para el censo de 1890 funcionaba con ellas). Un fichero en tarjetas perforadas es un bloque de tarjetas que tienen perforaciones que representan los caracteres que componen la información del registro. 
Los bloques de tarjetas se procesaban todos completos: se comenzaba a leer desde la primera tarjeta hasta alcanzar la última. Por tanto, si por algún motivo era necesario acceder exclusivamente a un registro, se debía leer secuencialmente todo el bloque, desde el principio, hasta llegar a él.

### Nivel de adopción.
Hoy en día los archivos son una parte esencial de nuestra vida diaria, tanto a nivel personal como profesional. Se utilizan en una variedad de contextos, desde la gestión de datos corporativos hasta el almacenamiento de fotografías y vídeos personales. La seguridad de los archivos y la protección de datos también se han convertido en temas importantes, con énfasis en el cifrado y la protección de datos.
En resumen, el uso de archivos ha aumentado y cambiado mucho a lo largo de la historia, según las necesidades tecnológicas y sociales de cada época.

### Descripción del funcionamiento del sistema de almacenamiento
La información se organiza en estructuras de datos, que pueden ser simples o complejas. Por ejemplo, un archivo de texto almacena caracteres en una matriz lineal, mientras que un archivo de base de datos puede contener tablas con filas y columnas.
En un dispositivo de almacenamiento, los archivos se organizan en un sistema de archivos. Este sistema gestiona cómo se almacenan y recuperan los archivos, asigna espacio en disco y mantiene una lista de archivos disponibles.
La información se puede codificar y comprimir para optimizar el espacio de almacenamiento. La compresión reduce el tamaño del archivo, lo que permite almacenar más datos en menos espacio.

### Ventajas e inconvenientes
Ventajas:
1. Homogeneización de documentos.
2. Ahorro de espacio físico y tiempo.
3. Mayor eficiencia en la gestión empresarial.
4. Resguardo seguro de documentos.
5. Eliminación de riesgos.

Desventajas:
1. Dificultad en el acceso a los datos.
2. Aislamiento de datos.
3. Anomalías en el acceso concurrente.
4. Problemas de integridad.

### Usos
Un fichero es un registro en el que se van a recoger y almacenar los datos que quieras guardar en él
Es un contenedor de información. La mayoría de los archivos que se utilizan contienen información en un formato determinado: un documento, una hoja de cálculo, un gráfico. El formato es la disposición de los datos dentro del archivo. El formato del archivo se conoce como tipo de datos.
Cuando el Gestor de archivos está en uno de sus modos de vista de iconos, puede identificar el tipo de datos de un archivo por el icono que se utiliza para representar el archivo. Cada tipo de datos tiene un icono diferente.

## Tipos: Tipos de ficheros, bases de datos representativas, etc.
Existen prácticamente infinitos tipos de ficheros pero los mas comunes son :
Texto: txt, md, rtf…
Ofimática: docx, xlsx, pptx, odt, ods, odp…
Imagen: jpg, gif, bmp, png, heic, webp…
Vídeo: avi, mov, mp4, mpeg, wmv…
Ejecución del sistema: exe, bat, dll, sys…
Audio: mp3, aac, ogg, wav, wma…
Archivo comprimido: zip, rar, tar…
Lectura: pdf, epub, azw, ibook…
Imagen de disco: iso, mds, img…

### Casos de uso reales observados (mínimo 3 ejemplos)
los casos de uso de ficheros describen situaciones específicas en las que se utilizan archivos para cumplir con ciertos objetivos, como almacenar, intercambiar o procesar información.
ejemplos:  Almacenamiento de Configuraciones, Exportación de Datos y Registro de Actividades

# Tipos de almacenamiento

## Bases de datos no relacionales
### Alumnos que han participado
`Miguel Fernández Vallés y Jorge Fresno Menéndez`
### Origen. ¿Cuándo surgió? ¿Cómo se popularizó?
Surgen como respuesta a las limitaciones que tienen las bases de datos relacionales. Se crean en 1998, no por una empresa o entidad particular si no por diferentes empresas como Google, Amazon, Facebook... y creadores de grandes proyectos open source como MongoDB, Cassandra... solucionando las carencias de las RDBMS.

Comenzaron a ganar relevancia a mediados de la década de 2000, impulsadas por la necesidad de almacenar y procesar grandes volúmenes de datos generados por aplicaciones web 2.0, redes sociales y el Internet de las Cosas (IoT).

### Nivel de adopción
Aunque las bases de datos más usadas siguen siendo las relacionales, las bases de datos no relacionales han aumentado su uso hasta situar a MongoDB como la quinta base de datos más usada. Muchas empresas de todos los tamaños las utilizan para diversas aplicaciones, desde startups hasta grandes corporaciones. La elección de una base de datos NoSQL depende de las necesidades específicas de cada proyecto, como el tipo de datos, el volumen, la frecuencia de acceso y los requisitos de rendimiento.

Estas son las bases de datos más usadas, donde podemos ver a MongoDB en el quinto lugar:
![Bases más usadas](https://learnsql.es/blog/las-bases-de-datos-mas-populares-en-2023/most-popular-databases-2023-3.webp)

### Descripción del funcionamiento del sistema de almacenamiento
En lugar de utilizar tablas y relaciones con las bases de datos relacionales, emplean modelos de datos más flexibles como:

- ***Clave-Valor***: Cada dato se almacena como un par único de clave y valor. Por ejemplo una simple lista de compras donde cada ítem (clave) tiene asociado un valor (cantidad).
- ***Documentos***: Los documentos almacenan datos en un formato similar a JSON, lo que permite estructuras anidadas y flexibles. Esto significa que puedes tener objetos dentro de objetos, creando estructuras de datos más complejas y representativas de la información real.
- ***Columnas***: A diferencia de las bases de datos relacionales que organizan los datos en filas y columnas, las bases de datos de columnas invierten esta lógica. Los datos se organizan en columnas, y cada columna puede tener diferentes tipos de datos.
- ***Gráficos***: Los datos se representan como nodos (entidades) y relaciones (conexiones) entre ellos. Esto permite modelar datos con relaciones complejas y jerárquicas.

### Ventajas e incovenientes
**Ventajas**
1. *Escalabilidad*: Gracias a su escalabilidad horizontal frente a la vertical de las relacionales, en lugar de aumentar la potencial del servidor, puedes agregar más servidores para aumentar la carga de trabajo.
2. *Flexibilidad*: No se limitan a un esquema rígido, permitiendo adaptarse fácilmente a los cambios en datos y nuevos tipos de información.
3. *Rendimiento optimizado*: Al diseñarse para un tipo específico de trabajo, pueden ofrecer un rendimiento superior en ciertas operaciones, como lecturas y escrituras de alta velocidad.
4.  *Economía*: No se necesitan servidores con gran cantidad de recursos para operar.

**Desventajas**
1. *Madurez*: Algunas bases de datos NoSQL aún están en desarrollo y pueden carecer de algunas características o funcionalidades.
2. *Falta de estándares*: : No se tiene un criterio plenamente definido, variando el lenguaje según el tipo de base de datos que se vaya a utilizar.
3. *Complejidad*: La gestión es más compleja que en una base de datos relacional.
4. *Herramientas GUI:*  La mayoría de las bases de datos NoSQL no contienen una interfaz gráfica. Requiere conocimiento especial para poder ejecutarlas.

### Usos
Una base de datos NoSQL es la mejor opción para gestionar datos indeterminados, no relacionados o que cambian rápidamente. Pueden usarse para aplicaciones que cumplan:
+ Necesidad de esquemas flexibles que permitan un desarrollo más rápido e iterativo.
+ Realizar consultas complejas y uniones entre tablas.
+ Exigencia de un escalado horizontal mediante la fragmentación de los servidores.
+ Alto nivel de integridad de los datos y transacciones ACID (atomicidad, coherencia, aislamiento y durabilidad).

### Tipos
#### Bases de datos clave-valor
Son las más sencillas de todas y almacenan datos en una organización de pares de clave y valor. Son las que permiten más altas velocidades en la lectura y escritura de datos y se usan principalmente en sistemas de almacenamiento en caché.

![Clave-valor](https://www.certia.net/wp-content/uploads/2021/03/Clave_Valor.jpg)
#### Bases de datos de documentos
Las bases de datos de documentos almacenan datos en colecciones, siendo los elementos de cada una de esas colecciones documentos que contienen pares clave/valor. Además de también tener un identificador único para cada documento, los campos de los que consta este documento sí son transparentes para el sistema de administración.

![Documentos](https://www.certia.net/wp-content/uploads/2021/03/Documento-JSON.jpg)
#### Bases de datos de columnas anchas
Están pensadas para requerir menos consultas a la hora de recuperar datos puesto que guardan todos los datos relacionados en “grupos”, teniendo cada familia de columnas un conjunto de columnas con una relación lógica entre ellas.

![Columnas](https://www.certia.net/wp-content/uploads/2021/03/Familia-columnas.jpg)
#### Bases de datos orientadas a grafos
Están compuestas por documentos que se relacionan entre sí y que permiten representar relaciones complejas entre los datos y así realizar consultas eficientes a través de los nodos y aristas analizando sus relaciones.

![Grafos](https://www.certia.net/wp-content/uploads/2021/03/Grafos.png)

### Casos de uso reales observados
1. **Redes sociales**

![Redes](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTQKrFhY-ljA-u7J5IMWeTv8zmpBx4PP9nQMw&s)

Facebook utiliza Cassandra para manejar los datos generados por usuarios como comentarios, likes, publicaciones...X utiliza también Cassandra y Storm para procesar en tiempo real los tweets y construir un índice de búsqueda invertido.

2. **Comercio electrónico**

![Comercio](https://brandemia.org/contenido/subidas/2022/11/logo-amazon-2000-actualidad-1024x576.png)

Utiliza DynamoDB para almacenar información de productos, pedidos, recomendaciones y datos de clientes en tiempo real. Esto les permite ofrecer una experiencia de compra personalizada y escalable.

3. **Juegos en Línea**

![Juego](https://brand.riotgames.com/static/a91000434ed683358004b85c95d43ce0/8a20a/lol-logo.png)

Riot Games emplea Cassandra para manejar la gran cantidad de datos generados por League of Legends, como estadísticas de partidas, perfiles de jugadores y chat.

Blizzard Entertainment utiliza MongoDB para almacenar datos de los jugadores, como personajes, inventario y progreso en el juego.

4. **Plataformas de streaming**

![Netflix](https://m.media-amazon.com/images/I/51LGj5--KsL.png)

Netflix emplea Cassandra para almacenar datos de usuarios, como historial de visualización, calificaciones y recomendaciones. También utiliza Elasticsearch para realizar búsquedas de contenido.

## TAREA 1 | TEMA DEL GRUPO | BASE DE DATOS DE OBJETOS
 
### Autores: 
Carmen y Judith
 
### Origen, ¿Cuándo surgió? ¿Cómo se popularizó?:

Las bases de datos de objetos surgieron en la década de 1960, gracias a los esfuerzos de Kristen Nygaard y Ole-Johan Dahl, pioneros en el desarrollo de sistemas informáticos. Su objetivo era crear un software que replicara fielmente los objetos físicos en un entorno digital, lo que llevó a la creación del lenguaje de programación Simula-67. 
La popularización de las bases de datos de objetos se produjo en los años 80, impulsada por Alan Kay y Xerox. Utilizando Simula-67 como base, desarrollaron Smalltalk, un lenguaje que eventualmente influyó en la creación de C++. 
En la actualidad, las bases de datos de objetos están recuperando relevancia debido a la creciente demanda de aplicaciones que emplean lenguajes de programación orientados a objetos y al apoyo de las comunidades de software libre y POO. 


### Nivel de adopción:

El uso de las bases de datos orientadas a objetos es relativamente limitado en comparación con las bases de datos relacionales. Su aplicación se centra principalmente en áreas que manejan grandes volúmenes de datos complejos y requieren una representación precisa de objetos del mundo real, como en ingeniería y diseño. 
 
### Descripción del funcionamiento del sistema de almacenamiento:

En términos generales, estas bases de datos utilizan la programación orientada a objetos para almacenar y gestionar datos. 

Componentes y Funcionamiento: 

-  Almacenamiento de Objetos 

   - En lugar de utilizar tablas, las bases de datos orientadas a objetos almacenan los datos en forma de objetos, que son instancias de clases con propiedades y métodos definidos. 

- Integridad de Datos 

  - Implementan mecanismos para asegurar la integridad de los datos, como la gestión de transacciones, control de concurrencia y recuperación ante fallos. 

- Persistencia de Objetos 

  - Los objetos creados bajo este modelo pueden ser almacenados directamente en la base de datos sin necesidad de convertirlos a otro formato, como filas o columnas. 

- Consultas 

  - A diferencia de las bases de datos relacionales, estas utilizan lenguajes de consulta orientados a objetos, que permiten realizar consultas complejas sobre los objetos y sus relaciones. 

 
### Ventajas e inconvenientes:

- Ventajas
  - Son perfectas para trabajar con lenguajes de programación orientados a objetos, facilitando su integración en la base de datos.
  - Permiten manipular conjuntos de datos complejos de manera rápida y eficiente.
  - Cada objeto tiene un identificador único asignado.
  - Las transacciones ACID se completan sólo cuando no hay conflictos entre los datos.
  - Cuentan con un sistema de memoria caché que agiliza su uso.
  - Son capaces de manejar grandes volúmenes de datos.

 - Desventajas
   - Su uso no está muy extendido.
   - Si no están bien optimizadas, pueden ser menos eficientes que las bases de datos relacionales.
   - No tienen estándares claros y definidos.
   - Existe poca documentación disponible.
   - Tienen una curva de aprendizaje pronunciada. 
 
### Usos:

La utilización de las bases de datos orientadas a objetos se limita a áreas muy específicas, como la ingeniería, las telecomunicaciones y la biología molecular, porque permiten una manipulación y visualización de datos mucho más sencilla y directa. 

En resumen, su uso se centra en el almacenamiento y manejo de datos muy complejos y/o voluminosos, permitiendo establecer relaciones directas entre los datos, sin necesidad de distribuirlos en tablas como en las bases de datos tradicionales. 
 
### Tipos: Tipos de ficheros, bases de datos representativas, etc:

- Ficheros de objetos puros
   - Almacenan objetos completos, incluyendo sus atributos y métodos

 - Ficheros de objetos relacionales
   - Combinan las caracteristicas de diferentes modelos de bases de datos y pueden manejar tanto datos estructurados como no esctructurados

- Bases de Datos Representativas
  - Db4o
     - Base de datos orientada a objetos, ideal para Java y .NET.
  - ObjectDB
     -  Optimizada para aplicaciones Java.
  - Versant Object Database
     - Ofrece gran rendimiento y escalabilidad, utilizada en aplicaciones empresariales.
  - GemStone/S
     - Soporta Smalltalk, adecuada para aplicaciones críticas. 

### Casos de uso reales observados:

- Caso 1: Gestión de Usuarios en una Aplicación Web
   - Cada usuario es un objeto con atributos como nombre, email, contraseña y métodos como actualizarPerfil() o verificarContraseña(). Los usuarios administradores heredan de la clase Usuario, añadiendo métodos para gestionar permisos y otros usuarios.

- Caso 2: Sistema de Gestión de Proyectos de Software
  - Los proyectos se representan como objetos que contienen otros objetos, como tareas, archivos y colaboradores. Cada proyecto tiene atributos como nombre, fecha de entrega, y métodos como agregarTarea() o asignarColaborador(). 

- Caso 3: Gestión de Recursos Multimedia en un Servidor
  - Los proyectos se representan como objetos que contienen otros objetos, como tareas, archivos y colaboradores. Cada proyecto tiene atributos como nombre, fecha de entrega, y métodos como agregarTarea() o asignarColaborador().


## Bases de Datos Orientadas a Objetos (BDOO)

### Autores
* Luis Iturrioz López
* David Fernández Suco

### Origen y Popularización
El origen se remonta a la década de los 70 con los primeros lenguajes de programación orientados a objetos, pero el término “base de datos orientado a objetos” no nació hasta el 85. La popularización se dio en parte por el aumento de aplicaciones que requerían manejar datos complejos, como gráficos, multimedia y sistemas CAD. Además, la proliferación de lenguajes de programación orientados a objetos, como C++ y Java, facilitó su adopción.

### Nivel de Adopción
La adopción es limitada, aunque tiene ciertos nichos donde son populares, como cuando se trabaja con datos complejos, pero en general distan bastante de estar adoptadas a gran escala. 

### Descripción del funcionamiento del sistema de almacenamiento
Funcionan agrupando en paquetes relacionados la información, estos paquetes son objetos que almacenan la información, a diferencia de otras bases de datos que guardan su información en filas y columnas. Las BDOO emplean lenguajes de programación y se pueden aplicar métodos, clases y subclases.

### Ventajas e inconvenientes
* **Ventajas:**
    * Mayor capacidad de modelado: Representan el mundo real de forma más intuitiva 
    * Flexibilidad: Permiten adaptarse a cambios en los requisitos de una aplicación
    * Manejo de datos complejos: Son ideales para gestionar datos de gran tamaño y complejidad. 
    * Integración con lenguajes orientados a objetos: La integración con lenguajes como Java o C++ es más natural 
    * Reutilización de código: Al permitir la creación de clases y jerarquías de clases, se promueve la reutilización de código. 
* **Inconvenientes:**
    * Complejidad: Requiere un mayor conocimiento y experiencia por parte de los desarrolladores. 
    * Madurez: Las BDOO aún no están tan maduras como las bases de datos relacionales, lo que puede implicar una menor disponibilidad de herramientas y soporte. 
    * Rendimiento: En algunos casos, el rendimiento de las BDOO puede ser inferior al de las bases de datos relacionales, especialmente en consultas complejas
    * Falta de un estándar universal: No existe un estándar universal para las BDOO, lo que dificulta la portabilidad de las aplicaciones entre diferentes sistemas.
    * Costo: Las licencias de los sistemas de gestión de bases de datos orientados a objetos suelen ser más costosas que las de los sistemas relacionales.

### Usos
* Modelado de datos complejos: Son ideales para representar entidades del mundo real con sus atributos y relaciones de manera intuitiva.  
* Gestión de datos multimedia: Gracias a su capacidad para almacenar objetos complejos, son excelentes para manejar imágenes, videos, audio y otros tipos de datos multimedia.
* Gestión de información geográfica (GIS): Los sistemas GIS utilizan BDOO para modelar entidades geográficas como puntos, líneas y polígonos, así como sus atributos y relaciones espaciales. 
* Aplicaciones CAD/CAM: En el diseño asistido por computadora (CAD) y la fabricación asistida por computadora (CAM), permiten representar de forma precisa objetos tridimensionales y sus relaciones geométricas. 
* Inteligencia artificial: Son útiles en aplicaciones de inteligencia artificial, como sistemas expertos y redes neuronales, para representar el conocimiento y los datos de manera estructurada. 

### Tipos
* **BDOO Puras:**
    * Definición: Implementan de forma completa los conceptos de la programación orientada a objetos, como la herencia, el polimorfismo y la encapsulación.
    * Características: Ofrecen un alto nivel de abstracción y una estrecha integración con los lenguajes de programación orientados a objetos.
* **BDOO Híbridas:**
    * Definición: Combinan características de las bases de datos relacionales y orientaadas a objetos.
    * Características: Ofrecen un equilibrio entre la flexibilidad de las BDOO y la eficiencia de las bases de datos relacionales.
* **Objetos-Relacionales:**
    * Definición: Son una evolución de las bases de datos relacionales que añaden soporte para tipos de datos complejos y objetos.
    * Características: Permiten almacenar y manipular tanto datos estructurados como no estructurados, ofreciendo una mayor flexibilidad.

### Casos de uso reales
* **CATIA (CAD)** utiliza BDOO para gestionar la información de los diseños, desde piezas individuales hasta ensamblajes completos. Esto facilita la creación de configuraciones, variantes y la gestión del ciclo de vida del producto.
* **ArcGIS (GIS)** utiliza BDOO para almacenar y gestionar la información geográfica. Por ejemplo, un río puede ser representado como un objeto con atributos como longitud, caudal y calidad del agua, y relacionado con otros objetos como puentes o ciudades.
* **BioJava (Bioinformática)** utiliza BDOO para representar secuencias de proteínas, estructuras 3D y vías metabólicas. Esto facilita el análisis y la comparación de datos biológicos. 

