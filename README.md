# NoSQL_Cassandra


Este proyecto es sobre dos conjuntos de datos que contienen diferentes charlas TED. Los ficheros con los que he trabajado són:

- transcripts.csv
- ted.csv

En el fichero "transcript.csv" se encuentran las charlas completas y en "ted.csv" datos sobre cada una de estas charlas. 
Para poder unificar estos dos ficheros he realizado un JOIN con la única columna que coincide entre los dos, que es la URL.

A partir de aquí lo que he ido haciendo ha sido preparar las tablas con los datos necesarios para posteriormente realizar las consultas
fácilmente. 
Tal y como se ve en el "notebook" he separado el tratado de los datos para que se vea mucho más claro el proceso llevado a cabo.
Una vez acabado ésto último, ya he procedido a conectar con la máquina donde se encuentra la base de datos Cassandra, la creación de cada 
una de las tablas con sus correspondientes inserts de los datos anteriores ya comentados y par finalizar, las consultas de cada una de las
cosas que se piden.



