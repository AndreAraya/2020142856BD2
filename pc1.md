Instituto Tecnológico de Costa Rica

Ingeniería en Computación.

**Bases de Datos II.**

1er semestre

**Prueba Corta #1**

**ESTUDIANTE:**

Edgar André Araya Vargas

2020142856

**PROFESOR:**

Gerardo Nereo Campos Araya

Grupo: 1

Fecha de entrega:

Martes 28 de febrero del 2023.

### 1. Explique cómo afectan los siguientes componentes el rendimiento de un sistema de base de datos: 

#### a. Disco
Donde se almacenan la mayor cantidad de datos de la base. Aquí se almacenan los File Descriptors para ser manejados por el File System, entre más File Descriptor más se le exige al file system y esta toma espacio del hard drive necesario para el funcionamiento de la base. Extremadamente lento comparado con memoria, utilizado con DMA (componente de hardware). Un componente al cual tenerle cuidado.

#### b. Memoria Virtual 
Las bases de datos a menudo requieren grandes cantidades de memoria para almacenar y procesar datos, y la memoria virtual puede ayudar a administrar esta demanda al permitir que el sistema operativo asigne más memoria a la base de datos cuando sea necesario sin agregar memoria física al sistema. Esto ayuda a evitar fallas y otros errores relacionados con la memoria que pueden ocurrir cuando el sistema se queda sin memoria física

#### c. Memoria 
Memoria extremadamente rápida comparada con el disco. Dividida en espacio de sistema operativa y memoria de usuario. Las bases de datos generalmente requieren una gran cantidad de memoria para almacenar y procesar datos de manera eficiente. los datos se cargan en la memoria para un acceso más rápido. 
#### d. Caché de CPU 
A la hora de realizar instrucciones dentro del CPU en la base de datos se puede topar con consultas que llamen a información contenida en la Memoria de la base. Entrar a la memoria seria extremadamente lento por lo tanto se crear el cache. Reduce el impacto de tiempo en consultas en las bases de datos al almacenar datos importantes en el cache, incluso si el dato no existiera en el momento con el cache podemos hacer un switch en el CPU para permitir otra aplicación aprovechar los recursos.
#### e. CPU 
Recurso sumamente rápido comparado con la memoria, el mas caro. El CPU ejecuta las instrucciones a trabajar de la base de datos.

### 2. ¿De qué forma se benefician las aplicaciones del uso de caches? Explique.
En muchísimos casos el uso de un cache significa reducción de tiempo de consulta o mejor manejo de recursos lo cual proporciona a las aplicaciones mayor eficiencia y rapidez, mejor experiencia para el usuario. Al mismo tiempo, debido al beneficio del context switch varias aplicaciones corriendo en un teléfono con Caché de CPU pueden utilizar los recursos de los procesadores de mucho mejor manera, nuevamente mejorando la experiencia del usuario. 

### 3. Desde el punto de vista de Elasticsearch, ¿Que es un índice? 
En Elasticsearch se utiliza el índice como un espacio de nombres o un contenedor lógico que contiene una colección de documentos con características similares. Todos los documentos en Elasticsearch se almacena en un índice y tiene una identificación única. Esto hace a los indexes un tipo de organización de información. 

### 4. ¿Que es un mapping en Elasticsearch?
El mapping es un complemento al índice de Elasticsearch, mediante un mapping se definen los campos y tipos de datos de los documentos en el índice. El mapeo es importante porque le permite a Elasticsearch comprender qué datos se indexan y qué hacer con ellos. Cuando se indexan los datos, Elasticsearch usa asignaciones para determinar el tipo de datos de cada y como deben ser tratados.




