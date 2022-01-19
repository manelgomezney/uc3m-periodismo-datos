# Examen final de Periodismo de datos

Manel Gómez Ney


8. Qué saberes están implicados en periodismo de datos. Razona la respuesta.

En el Periodismo de datos podríamos hablar de tres elementos nucleares que implican distintos conocimientos.

Periodismo: obviamente, ya aparece en el nombre, pero hay que aclarar que pese a las nuevas tecnologías se siguen manteniendo los estándares de la profesión, especialmente 
el del carácter de todo ejercicio periodístico como una investigación sobre un determinado tema

Visualización: Quizá el más infravalorado de los tres puntos. Mucha gente podría interpretarlo como el proceso de transformación ulterior de toda la información 
transformada en un producto final que todo el mundo pueda comprender. Sin embargo, esto no es así, pues hay muchos procesos intermedios para ir filtrando los datos para que 
el propio profesional los pueda comprender mejor. Por lo tanto, intervienen muchas ramas del conocimiento, desde las fórmulas estadísticas a la propia informática, pasando 
por el diseño

Datos: Sandra Crucianelli hablaba de "periodismo de bases de datos", en referencia a que todos estos registros electrónicos parten de una base. Lo importante aquí es 
saber como manejarlos con la ayuda de los ordenadores para extraer información de ellos (véase el caso de los Papeles de Panamá, con millones de datos que los periodistas 
fueron tratando y analizando)


10. Qué tipos de interfaces de datos hay

Hay tres tipos de interfaces aunque hemos visto dos:

CLI de Command Line Interfaces o interfaces de línea de comandos (permite a los usuarios provocar acciones a cualquier programa informático o a un sistema operativo a partir de 
una línea de texto simple).

GUI de Graphical User Interfaces o interfaces gráficas de usuario (Utiliza una serie de imágenes u otros objetos gráficos para representar la información y acciones 
disponibles en la interfaz del usuario)

Las de los móviles, que son capacitivas.


11. Qué tipos de datos hay

Hay varios tipos de datos, comenzando por los "stringer", que son todos aquellos que se interpretan como texto a partir de una cadena de caracteres. También están los 
numéricos, que contienen (tal y como se indica en su nombre) números o elementos numéricos con los que se pueda elaborar operaciones matemáticas (en algunas ocasiones los 
números pueden ser también un texto, como en el caso de nuestros números de identificación en la universidad). Además, en este tipo se hallan diferentes subtipos. Están los 
"integer", que son números enteros, los "decimal" (números con pocos decimales y siempre el mismo número de estos para todos los datos de este tipo, por lo que son más 
lentos de procesar), los "float" (con decimales pero variables en el número de estos, por lo que su procesamiento es más veloz), los "date" o "datetime" (cuya forma más 
común es YYYY--MM--DD y YYYY-MM-DD-HH:MM:SS, respectivamente, pudiéndose indicar además el uso horario en cuestión con la letra Z en caso de que sea el horario UTC, y en 
caso contrario UTC+1 o UTC-1, dependiendo de la zona temporal en cuestión), y los "period", que hacen referencia a los datos periódicos, es decir, que se repiten en el 
tiempo (se indican con una P al principio del número y con otra al final, que puede ser Y, M, o D para saber si su repetición es anual, mensual o diaria, así como la T 
indicaría el tiempo si se tratara de horas, minutos o segundos).
Además, otro tipo de datos puede ser el de los "booleanos", que siguen la lógica binaria de "true" o "false".


12. ¿Qué significa el funcionamiento "cliente-servidor"?

La arquitectura cliente-servidor es un modelo de diseño de software en el que las tareas se reparten entre los proveedores de recursos o servicios, llamados servidores, y 
los demandantes, llamados clientes. Un cliente realiza peticiones a otro programa, el servidor, quien le da una respuesta. Esta idea es eficiente a nivel personal pero su 
mayor potencial se encuentra en el ámbito colaborativo o con varios servidores y clientes. Algunos ejemplos de aplicaciones que usen el modelo cliente-servidor son: correo 
electrónico, o la World Wide Web. Para ello, nuestro ordenador se reconoce a sí mismo como localhost.


15. Cuál fue el comienzo del CAR (Computer Assisted Reporting)?

Dicho comienzo se da en EEUU, en el año 1952, por parte de la cadena televisiva CBS ante las elecciones nacionales que iban a tener lugar. Ese año, se utilizó la computadora 
central UNIVAC (computadora automática universal I) para predecir el resultado de las elecciones mencionadas desde la Oficina del Censo y ser utilizada por primera vez en un 
evento promocional por la cadena CBS para predecir los resultados de las elecciones.

Las elecciones enfrentaron a Eisenhower contra Adlai Stevenson, y las encuestas de opinión favorecían a Stevenson. La predicción temprana de la computadora, realizada antes 
de que se cerraran las urnas en la costa oeste, fue que Eisenhower obtendría más de 400 votos y que tenía unas probabilidades de ganar de 100 a una, cosa que en un principio 
nadie creyó hasta que, efectivamente, Eisenhower ganó con una ventaja ligeramente mayor de la señalada.

Este hito demostró el potencial de las computadoras para realizar análisis y predicciones, por lo que se inició una nueva corriente dentro del periodismo dispuesta a 
utilizar todos los recursos de esta tecnología en un mundo con cada vez más datos.


20. ¿Qué es nano?

nano es un editor en línea de comandos que se utiliza desde la terminal. Además de escribir, puedes realizar diversas acciones que permiten manejar el texto con mayor 
fluidez, además de contar con la ventaja de que estás generando el archivo (tenga el formato que tenga) dentro del directorio que tú quieras, sin necesidad de conexión a 
internet.


25. Si quisieras ver la web theguardian.com, ¿cómo lo harías desde la línea de comandos?

Utilizaría el comando "lynx" para acceder a esta, escribiendo en mi terminal: lynx www.theguardian.com, lo cual me conduciría directamente a esta.


28. ¿Cómo verías las variable de entorno de tu shell "PATH"? Escribe su valor también.

Utilizaría el comando "echo", escribiendo en mi terminal: "echo $PATH". En este caso, echo sirve para reproducir textualmente lo que se le indica, en este caso la variable 
(y por eso el símbolo "$") PATH. Su valor, en este caso, es: /usr/local/opt/openssl@1.1/bin:/usr/local/opt/openssl@1.1/bin:/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin


29. Cuál es el primer comando que deberías usar en la terminal. Explica tu respuesta.

Paradójicamente, el primer comando que deberías aprender es un gestor de comandos, es decir, un software encargado de almacenar distintos comandos que puedas instalar 
con facilidad en tu terminal. En el caso de Windows, apt-cyg. En el caso de MacOSX, Brew. De no ser así, para cada comando habría que ir a su correspondiente página web y 
descargarlo de ahí. En cambio estos gestores agilizan el proceso. En mi ordenador, si quisiera instalarme el comando "lolcat", me bastaría con escribir en mi terminal "brew 
install lolcat".


33. ¿Qué 3 tipos de formatos de datos hemos visto? ¿Que similitudes y diferencias tienen?

1. *SV o valores separados por cualquier valor. Aquí incluiríamos los conocidos CSV, TSV o PSV. 
2. JSON o JavaScript Object Notation, notación de objetos JS. Java es el lenguaje de programación más utilizado en la web, especialmente en entornos interactivos, así que es bastante frecuente. 
3. XML o eXtensible Markup Language, lenguaje de marcas extensible. Que es en el que se inspira excel en su formato XLSX.


36. ¿Que tipo de dato de fecha elegirías para tus archivos? Razona tu respuesta.

El más estandarizado, es decir, el ya mencionado anteriormente YYYY-MM-DD. Antes no lo he explicado, pero la Y equivaldría al año, la M al mes, la D al día. Utilizar el más 
estandarizado nos permitirá compartirlo con otras personas de una manera más fácil, no explicitando horas y segundos ya que, en la mayoría de los casos no suele ser la 
prioridad, aunque habría que evaluarlo previamente.


40. ¿Cómo creamos un directorio? ¿Y dos directorios? Razona tu respuesta.

Utilizaremos el comando "mkdir", escribiendo en el primer caso, en el directorio que queramos, "mkdir directorio-1", creándose una carpeta con dicho nombre. Para crear dos 
directorios hay dos formas de hacerlo, aunque es con el mismo comando: "mkdir directorio-1 directorio-2" para crear dos directorios distintos en el mismo lugar o "mkdir 
directorio-1/directorio-2" si queremos que el segundo directorio este dentro del primero.


43. Qué son las entidades HTML y cómo se representan. Por un ejemplo.

En algunas ocasiones hay ciertos caracteres que no se pueden escribir de forma literal en ciertos contextos, dado que el ordenador los interpreta de otra forma (como una 
orden determinada en el caso de HTML). Las entidades HTML son un conjunto de caracteres o string que empiezan por un ampersand & (y) terminan con un ; (punto y coma. Por 
ejemplo, el carácter á se escribe "&aacute;". Las entidades HTML también nos sirven para conocer que en todos los lenguajes informáticos existen los caracteres reservados, 
es decir, caracteres que no podemos usar tal cual porque el lenguaje los entiende de una manera especial.


44. Dado el significado que tienen las comillas para el comando =echo=, cómo harías para que devolviera una frase como: "Hola Mundo"

Utilizaría las entidades HTML de las que he hablado en la pregunta anterior. En este caso escribiría: echo &#168;Hola Mundo&#168;. Aunque, en realidad, hay otras formas más 
breves como colocar la "\" antes de cada una de las comillas.


45. Pon un ejemplo de uso de "wildcards"

Cuando hablamos de "wildcards" hablamos de comodines, es decir, de un código que puede ser interpretado de múltiples formas. En este caso, un ejemplo sería con mv *.json (el 
ordenador interpretaría que debería ejecutar este comando con todos los archivos con formato ".json" y los transportaría todos al lugar señalado, siendo en este caso "*" el 
comodín utilizado.


46. ¿Qué función tiene la almohadilla en Markdown y en un programa de la shell? Razona tu respuesta.

En los archivos de configuración de la Shell, si aparece una almohadilla al principio de línea quiere decir que se nos está comentando algo, es decir, que no la va a leer el 
programa que quiera leerla para hacer algo, sino que es algo que veremos nosotros. Por su parte, en Markdown dicho caracter es el equivalente del elemento h1 en HTML, 
también conocido como "encabezamiento de primer nivel" (lo de "primer nivel" varía según el número de almohadillas utilizadas).


48. ¿Cuál es el nombre de tu cuenta para localhost?

En este caso efectuaremos el comando "whoami" para conocer la respuesta, que es manelgomezney, es decir, mi nombre de usuario.


49. ¿Cómo mandas la salida del comando =echo= a =lolcat=?

Utilizando la barra vertical "|", y colocando el comando "lolcat" en último lugar. Un ejemplo: echo hola | lolcat


52. ¿Cómo ves todos los dialectos de la shell disponibles?

Podemos utilizar el comando "cat", de esta forma, con "cat /etc/shells" nos aparecerán todos los dialectos disponibles.


53. Pon un par de ejemplos de Google Dorks u "operadores de búsqueda"

Los operadores de búsqueda son una herramienta añadida a todo buscador que nos permite hacer búsquedas más precisas ayudandonos de códigos concretos. El operador "and", por 
ejemplo, si escribimos en la barra del buscador "X and Y", buscaría X e Y, no dándonos en ningún caso algún resultado que no contenga ninguno de los valores o solo uno de 
ellos. Otro operador (y este es muy útil) es el de "filetype:", que sirve para buscar algún tipo de archivo concreto según su formato. Si escribo en el buscador "github 
filetype:pdf", entonces solo me aparecerán archivos en formato .pdf relacionados con Github


54. Cómo realizas algún cambio en tu repositorio local y lo actualizas también en Github. Explica los pasos.

Primero debes situarte en el directorio donde se encuentran los archivos que has modificado. El primer paso será utilizar el comando Git add "archivo-en-cuestion", para 
indicar que este es el archivo que quieres actualizar. A continuación, utilizarás el comando Git commit -m "cambios-realizados" donde concretarás entre las comillas las 
modificaciones realizadas para que aparezcan en Github. Finalmente, utilizarás el comando Git push origin main, para que, en caso de tener el repositorio vinculado, se 
actualice automáticamente. En caso de cualquier error, puedes consultar lo ocurrido y los pasos necesarios con el comando "Git status"


58. Explica en qué situación te encuentras en cuanto al conocimiento de la terminal y el gestor de paquetes que utilices. Explica la respuesta.

En mi caso, el dominio de la terminal se ha visto incrementado exponencialmente en los últimos meses (antes no sabía ni de su existencia), hasta el punto en el que ahora me 
manejo bastante bien con ciertos comandos que me permiten agilizar la visualización de ciertos archivos, como "cat", "tail" o "head", gozando además de unas aptitudes 
notables en el manejo convergente con Github (gracias a las prácticas). Además, el brew no es excesivamente difícil de utilizar una vez instalado, y para incrementar mis 
conocimientos solo tengo que buscar los comandos por internet. Aún así, diré que este ordenador tiene un sistema operativo ligeramente antiguo (MacOS Hihg Sierra 10.13.6), y 
en el caso de algunos comandos no me deja descargármelos o usarlos adecuadamente, como "parrot.live".



59. Explica en qué situación te encuentras en cuanto al conocimiento de nano. Explica la respuesta.

Mi manejo con este editor de textos es bastante bueno. Así pues, este exxamen lo estoy escribiendo directamente desde ahí, y aunque no domino todos los comandos que me 
aparecen en la barra inferior, manejo los minimos indispensables que utilizaría en otro procesador como M$ Word, es decir guardar, copiar, pegar e incluso localizar ciertas 
palabras... con el añadido de que ante cualquier duda puedo acceder al manual apretando "^X" (donde ^es "Ctrl")



61. Describe los datos que estamos utilizando en el proyecto TRESCA. Qué tipo de archivo y qué tipo de datos.

En el archivo feliz.csv, que es el que utilizamos del proyecto TRESCA, nos encontramos con datos numéricos y de texto, en un archivo de CSV, es decir, Comma Separated 
Values. Esto hace que a la hora de limpiar el archivo para encontrar los datos buscados con Open Refine u otro software sea fácil para este interpretar cómo los queremos 
visualizar. En el caso de los datos numéricos, nos aparecen en formato "integer" con la coma para indicar el millar, y en formato "datetime" para indicarnos fecha y hora.


62. Explica la diferencia entre filas y columnas

Esto en clase se nos explicó mediante el listado con todos los alumnos. Cuando hablamos de filas y columnas hablamos de datos en una tabla. La tabla es una forma de 
visualizar dato que se lee de izquierda a derecha y de arriba a abajo. La lectura horizontal se corresponde a las filas y la vertical a las columnas. Las filas son las 
"líneas" del archivo que contiene los datos y en ocasiones, no tiene por qué cumplirse siempre, la primera línea hace de cabecera de la tabla e indica qué información tiene 
cada columna. La información de la columna está relacionada con el tipo de datos que tiene la tabla, es decir que su papel equivale a agrupar las distintas variables en los 
datos. Finalmente, en cada intersección de fila y columna se crea una casilla que llamamos "celda".



66. Qué es una faceta temporal

Es una herramienta del software OpenRefine que sirve para crear un intérvalo de tiempo a partir del cual podemos filtrar datos que estén dentro o fuera de dicho intérvalo. 
Para ello, es muy importante especificar previamente el tipo de datos que se dará en cada columna, puesto que la faceta temporal solo sirve para datos con un formato de 
fecha (en feliz.csv nos era muy útil ya que había una columna con datos en formato "datetime").


68. Como convertirías markdown a html desde pandoc

Escribiría en la terminal "pandoc archivo.md archivo.html". Pandoc tiene además distintas opciones añadidas para concretar mejor esa conversión.


71. Para qué usas cd y cómo.

Cd es un comando vital en la terminal, ya que con este nos podemos mover a través de los distintos directorios de nuestro ordenador con una agilidad y sencillez 
estremecedoras. Tan solo hay que saber donde está uno (puedo usar "pwd" para ver donde estoy o "ls" para listar posibles destinos) y escribir "cd nombre-del-directorio" y 
nos llevará hasta allí. Una de las principales ventajas de este comando es que, por otra parte, nos permite utilizar tanto rutas directas como indirectas. Así, puedo 
escribir "cd directorio-1/directorio-2" y también "cd ./directorio-1").


75. ¿Por qué es importante la visualización en el análisis de datos?

La visualización de los datos es uno de los tres elementos (y saberes) centrales en el periodismo de datos, y no solo hace referencia a la visualización como producto final. 
En la etapa de visualizar también debemos realizar distintos procesos de análisis, estudio, con fórmulas de carácter matemático y diversos programas informáticos que nos 
ayudan a lograr que de una ingente cantidad de datos seamos capaces de sacar hipótesis o conclusiones.


76. ¿Qué lenguajes informáticos conoces?

En el mundo de la informática debemos distinguir entre varios tipos de lenguajes. Puede estar el lenguaje estructurado como el HTML o XML o el lenguaje de programación, como 
Python o R, o C o C# o PHP, aunque el más utilizado es JavaScript dada su capacidad para generar entornos interactivos. Un lenguaje informático es, por cierto, todo ese 
conjunto de códigos que el ordenador es capaz de reconocer a través de su software, y que goza además de toda una serie de normas estandarizadas, comenzando por su sintaxis.


78. ¿Qué ha sido determinante para el nacimiento del periodismo de datos moderno?

El concepto contemporáneo de periodismo de datos llega entre los años 2006 y 2008, gracias a una combinación de factores como la abundancia de software de código abierto, el 
formato HTML5 y Open Data. Además, grandes medios de comunicación como El País (a nivel nacional) o The Guardian (a nivel internacional) han contriubuido a mostrarnos los 
beneficios de esta rama del periodismo que ha dado grandes nombres como el de Philip Meiler.


85. ¿Que significa TSV?

Tabula Separated Values, es un formato con el que podemos organizar los datos a través del tabulador, precedente del hoy más conocido Comma Separated Values (CSV). 
Utilizaban, para el TSV, el mayor espacio del tabulador para separar datos en las computadoras antiguas


97. Expón dos mejoras que has tenido en tu proceso de trabajo con el ordenador. Si en vez de mejoras ha sido lo contrario, exponlo también.

El tema de los buscadores me fue de gran ayuda, ya que últimamente no utilizo casi nada google y utilizo otros, en especial ecosia o duckduckgo si mi búsqueda es algo más 
compleja (mi sensación es que va mejor). Otra mejora sustancial se puede dar en el apartado de manejo y visualización de datos, ya que tanto OpenRefine como Datawrapper son 
herramientas muy útiles que antes no conocía, permitiéndome así comprender mejor no solo el periodismo de datos en sí sino el funcionamiento tan orgánico de los software.


100. ¿Quién es Philip Meyer?


De nacionalidad estadounidense, es uno de los periodistas de datos de referencia desde hace muchos años. Meyer utilizó durante su carrera periodística las nuevas tecnologías 
y uno de sus trabajos más sonados donde utilizó la asistencia de computadoras fue en los disturbios de Detroit de 1967. Su investigación, basado en encuestas, fueron 
analizadas en un ordenador y mostraron que las personas que habían asistido a la universidad tenían la misma propensión a amotinarse que los que abandonaban la escuela 
secundaria, algo que en su momento fue muy rompedor con lo que se pensaba. Actualmente trabaja como profesor en la Universidad de Carolina del Norte y sigue publicando en 
algunos medios como el USA Today. Hay que decir que en su caso siempre ha utilizado el término "periodismo de precisión" y no el de "periodismo de datos", aunque ambos son 
válidos y el primero se puede considerar un antecedente del segundo.


101. ¿Quién fue Florence Nightingale?

Una enfermera del siglo XIX que ya realizó unas primeras (y novedosas) investigaciones manejado un conjunto de datos. Se podría decir que prácticamente inventó los diagramas 
circulares (hay documentos que lo muestran) y que demostró en más de una ocasión como los datos, dentro de su profesión, podían salvar miles de vidas (en su caso para el 
ejército británico durante la Guerra de Crimea y posteriormente en la India). Su trabajo habría de inspirar grandes acciones y avances en muchos ámbitos, hasta el punto que 
se le atribuye la creación de la Cruz Roja (en palabras de su fundador).




