# funcionesAvanzadasSparkDataFrames
Funciones avanzadas de spark con pyspark

#Introducción:

Se presentan conceptos avanzados de Apache Spark, incluido el manejo de valores ausentes y la creación de funciones definidas por el usuario (UDF).
# Configuración del Entorno:

Se instala Java en el entorno y se configura la variable de entorno JAVA_HOME.
Se descarga y descomprime una versión específica de Spark.
Se instala y configura la biblioteca findspark.
Se inicia una sesión de Spark.
# Creación de DataFrames:

Se crean dos DataFrames de ejemplo: emp y dept, que contienen datos de empleados y departamentos, respectivamente.
Se registran estos DataFrames como vistas temporales y se guardan como tablas en HIVE.
# BroadCast Join:

Se discute el concepto de BroadCast Join y cómo se puede ajustar el tamaño de la tabla de transmisión.
Se muestra cómo realizar un BroadCast Join entre dos DataFrames de diferentes tamaños.
# Almacenamiento en Caché:

Se introduce el concepto de almacenamiento en caché para mejorar el rendimiento de las operaciones en Spark.
Se muestra cómo almacenar en caché un DataFrame y cómo verificar si un DataFrame está almacenado en caché o no.
# Expresiones SQL:

Se demuestra cómo usar expresiones SQL para manipular DataFrames en Spark.
Se muestra cómo categorizar los salarios de los empleados en diferentes niveles utilizando expresiones condicionales.
# Funciones Definidas por el Usuario (UDF):

Se introduce el concepto de UDF y se muestra cómo crear y usar una UDF para categorizar salarios.
# Trabajando con Valores NULL:

Se discuten varias funciones para manejar valores NULL en DataFrames, como isNull(), isNotNull(), fillna(), y dropna().
# Particionamiento:

Se discute el concepto de particionamiento en Spark y cómo controlar el número de particiones de un DataFrame.
# Catálogo de APIs:

Se presenta la API de Catálogo de Spark, que proporciona funciones para interactuar con bases de datos, tablas, columnas y funciones en Spark.
Se muestran varias funciones del catálogo, como listDatabases(), listTables(), listColumns(), listFunctions(), y más.
