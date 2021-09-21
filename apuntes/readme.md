 # Apuntes de periodismo de datos




## Clase práctica --- 15/09/2021 

Para agregar una carpeta en github, crea un archivo y en el título añade al final una barra tal como "/", la carpeta se crea automáticamente.

Tema 1.- Introducción al periodismo de datos

El periodismo de datos son periodistas aprendiendo a  hacer cosas con datos. ¿Por qué los periodistas necesitan ordenadores para trabajar con datos? Ben Wells  (Los Angeles Times y palewi.re).
Buena parte de la evolución de los departamentos de infografías se mezclan actualmente con los departamentos de datos. Pero hay estructuras empresariales donde a lo mejor está en el departamento de gráficos o de documentación, ya que para mostrar datos se requiere también una visualización de los mismos.  

Contexto histórico: Sociedad de la información.
Enn los años 60 se vive ya en "la sociedad de la información" según Daniel Bell. Igual esto ya se había mencionado antes pero este hombre escribió un libro que decía esto.  Todas las crisis actuales ponen en paréntesis dicha información,  donde se pasa de una sociedad industrial a una industria del conocimiento. Lo dicen tanto las cifras como los imperios mediáticos. No deja de haber una sociedad industrial que aporta el hardware a toda esta industria del conocimiento. "Estamos pasando y conviviendo de la prensa a la Web y del entorno del escritorio al portátil y a los dispositivos electrónicos móviles.

Las noticias también se han convertido en un elemento de consumo, como conocimiento pero también de entretenimiento y manipulación (fake news). 

Algunos de los inventos que demuestran esa confluencia entre la revolución industrial y la informacional:
-Máquina de vapor de Watt (1774)
-Telar de Jacquard (1801).
-La primera persona que programa en la historia: Ada Lovelace (1842)
-Algo importante en electrónica: la válvula de Fleming (1904)
-El transistor en 1930
-Cambio acelerado de hardware y software más autómatas durante la IIWW
-John von Neumann, arquitectura de ordenador, 1945
-Teoría matemática de la información de Shannon y Weaver (1948)
-Cibernética, internet, web.

¿Qué es Hardware? Lo físico, los aparatos, los dispositivos. ¿Qué es Software? La parte lógica, los programas que hacen que el Hardware funcionen, el sistema operativo.

Precedentes de la visualización de datos

Florence Nightingale (1820-1910): fue una enfermera, escritora y estadista, considerada pionera de la enfermería moderna, creadora del primer modelo conceptual de enfermería. Es por ello que se hace el año mundial de la enfermería. Limpiarse las manos antes de tocar a una persona enferma. Hizo gráficos para mostrar datos sobre los enfermos que tenían. Gráficos de Nightindale. Son como gráficos de quesitos con tres variables más la línea temporal.

Charles Minard (1781-1870): ingeniero y matemático francés. Gráfico conocido: campaña de Napoleón en Rusia. Ves como sale el ejército desde lituania, como va yendo hacia Moscú y la altura del trazo es proporcional al número de soldados que van cayendo. Es un gráfico que se puede proyectar sobre un mapa. Existe una correspondencia real. 
Gráficos de flujo:  sirve para ver flujos de migraciones y también lo hizo Minard (gráfico de flujos también con exportación de algodón y lana). Con este tipo de gráficas hay veces que no necesitamos muchos datos para hacer algo que realmente nos de información útil e interesante, que se explique por sí mismo y tenga un impacto.

John Snow: un médico y uno de los precursores de las enfermedades pandémicas, de la investigación de las enfermedades desconocidas. Si investigamos sobre él, hay cierta lucha entre las posiciones que mantenía John Snow y Nightindale. Esta última pertenecía a una escuela que sostenía que las miasmas son malas para la salud y entonces por eso abogaba por espacios higiénicos y limpios, eso hizo que las condiciones de salubridad de hospitales mejoraran. Snow no creía tanto en eso pero  también colaboró en mejorar la salubridad, en este caso con un gráfico, por ejemplo, de los casos de malaria, rompiendo directamente con la teoría miasmática o buscando la fuente del cólera, con un gráfico con los puntos principales de contagio. Es un caso paradigmático de visualización de datos que nos da pistas para investigar sobre  algo.

Hemos visto precedentes de la visualización de datos, ahora vamos al periodismo de datos como tal.

American slavery as it is: tratado abolicionista publicado en nueva york por la sociedad anti esclavista, junto con el anti immperialista. Muy ilustrados en la recopilación de datos que apoyaran sus tesis. Aportan aquí un ejemplo de como recopilar datos. Utilizaronb el anuncio "se busca", donde se daban datos de los esclavos para que pudieran ser reconocidos y pudieran volver a la plantación. Está disponible en archive.org y en la unc.edu. Otro antecedente de periodismo de datos no moderno es The Guardian o The Manchester Guardian.

Buscador que protege la privacidad: Duck duck go. Otro: starpage.com , hace búsquedas de google pero las anonimatiza para ti. Es un intermediario. Otro que es Ecosia, que planta árboles por cada número de búsquedas

Philip Meyer: el considerado iniciador del periodismo de datos pre-moderno. En los 60 y en los 70. El periodismo de precisión (así se le llama). Periodista del Miami Herald, queja del alto coste de los se3guros escolares contra incendios y huracanes. Realiza una investigación haciendo una tablita y resulta que el 75% de la financiación de las campañas electorales provenían de las empresas de seguros, una especie de pre-Bárcenas, alimentando la caja B de los partidos. Esto lo hizo con papel, no empleó máquinas porque no tenía instrumentos informáticos que le hicieran cálculos sobre esos datos. Vio que en el periodismo no se usaban dichas herramientas, y de ahí la foto con el IBM 7090, en el Harvard Computation Center. Este ordenador buscaba predecir los resultados electorales de Ohio, aunque sin éxito. 

Aún así, existía previamente ya en EEUU un precedente de periodismo asistido por ordenadores. 1952, recién terminada la IIWW, reordenando las industrias, hay un nuevo Hardware que es el UNIVAC que tiene tal capacidad de cómputo que puede predecir los resultados electorales. Electoralmente, se le daba vencedor a Stevenson, que salía vencedor en las encuestas. UNIVAC dijo que ganaría Eisenhower, para la sorpresa de los investigadores.

Philip Meyer intentó reproducir esto, pero no le salió, así que al final estudió los métodos de investigación de las ciencias sociales para aplicarlas al periodismo. Así usó su beca Nieman, que todavía hoy perdura (NiemanLab, que habla sobre periodismo en general). Cada estudiante tenía 20 segundos para utilizar el ordenador, pero çel consiguió unos cuantos más. La máquina trabajaba con datos tabulados (como el CSV en excel), datos que el ordenador es capaz de entender que hay una separación entre los mismos. Tenían el rpograma Harvard Data-Text, predecesor de SPSS  o "R" (el que usa Idaira en Criminología).

Philip Meyer salta a la fama definitivamente con "Detroit Riots", un largo y cálido verano plagado de disturbios donde acaban 46 personas muertas. Obligatorio ver la película "Detroit". Pilip Meyer tuvo la suerte de que en Wtts hubo una revuelta en el año 1965 (documental Wattstax, un concierto que se hizo después de las revueltas para hermanar a los bandos enfrentados), la universidad de California hizo un informe sobre esas revueltas. Meyer intentó hacer lo mismo pero en 2 semanas, misma metodología pero como labor periodística y no académica. Contrató a varios expertos de distintas ramas para recopilar datos, con el IBM 360/40 como ordenador. Con su investigación Detroit Riots da lugar al periodismo de precisión, desmontando la teoría Riff-Raff (considerada como la que provocó los disturbios de Detroit) y la teoría de la Assimilation (migración= conflicto)..

Ver cómo otras personas progresan mientras tu te estancas causa frustración. Esa fue de las principales causas de las revueltas.
El computer assisted reporting ha supuesto las aplicaciones informáticas a la hora de manejar grandes cantidades de información con herramientas analíticas más potentes en una sociedad con cada vez más abundancia de información (frase de Philip Meyer). El periodismo así queda elevado al nivel de la ciencia y del arte. El análisis se prioriza antes que la verdad. El periodismo de datos, que se define como tal en 2006 2007 o 2008 con el movimiento de los datos en abiertos, produciendo una enorme cantidad de datos para posibles investigaciones periodísticas.

Importante, conocer el NICAR: National Institute of Computer Assister Reporting. Un anexo del IRE, que montan todos los años un congreso nacional que es el NICAR. Philip Meyers acabó formando parte de esto.

En la próxima clase: periodismo de datos en España, como el grupo Medialab-Prado (un centro cultural importante).

## Clase teórica 21/09

En una tabla de datos necesitas datos. Existe el periodismo guiado por datos, una visión que persigue el periodismo a partir de la innovación. EL periodismo tiene que estar dando información verídica y no en invenciones, esto lo acerca más a ese ideal, además del periodismo de investigación. Este periodismo alude a que hoy en día tenemos una gran cantidad de datos, más cuando empezaba que buena parte de los gobiernos e instituciones tenían los datos en abierto (leyes de transparencia a partir de 2013). Hay una gran disponibilidad de toda la administraci
ón pública de datos.
Hay datos que no están a disposición de la ciudadanía, pero tenemos el derecho a hacer una petición de transparencia aunque no sea exitosa. Hay una serie de supuestos que pueden impedírnoslo. Ley de datos personales. 
1989: el mundo de los bases de datos estructuradas se pone en boga, en aquel momento se empieza a conocer como periodismo de base de datos. Sandra Cruccianelli, formadora y docento.
CSV: Valores separados por comas. Philipp Meyer usaba un programa que se llamaba Filter Tau, parecido a Mark Down, una sintaxis simple pero a la vez un programa que permite transformar una sintaxis en otras sintaxis estructuradas. Es una sintaxis para "lenguaje natural", lo que en términos de tipos de datos sería "strings", o cadenas de caracteres. Filter tau se utilizaba para trabajar con datos. Al principio, por lo que pfuese (visualmente en la pantalla se podría separar mejor) era el tabulador. Por eso antes se hablaba de TSV (Tabulation separated values), así como de *SV (valores separados por cualquier caracter, en España el más utillizado es el punto y coma)*. 
También es muy interesante el tema de los permisos, pero ya lo trataremos.

Hay tres tipos fundamentales de formatos de datos, sacando fuera las bases de datos SQL (un mundo aparte): Los *SV (*), los JSON y los XML (en el que se basa el hatml, lenguaje de marcado generalizado, un lenguaje que va a estructurar texto). XML, una especie de puente entre el mundo del texto y el lenguaje de los datos. Es un lenguaje de marcas extensible para hacer una réplica de base de datos SQL.
Los JSON son también en modo texto: Java Script Object Notation. No lo vamos a utilizar porque no nos da tiempo pero también existe.

Independientemente del formato, llegamos a otro tema que son los tipos de datos. No todos los CSV están listos para usarse. La mayor parte del tiempo se dedica limpiando los datos. Lectura de izquierda a derecha y de arriba a abajo. Hay filas y columnas. (rows and columns). La primera fila te indica qué tipo de información hay en cada columna, que suele separar los tipos de informaciones.
Por ejemplo: si en una columna están todos los NIU de la clase, no serán números como tal porque aunque en realidad lo sean, no podremos operar con ellos sino que serán más bien caracteres identificadores. Esto demuestra que los números son un tipo concreto de datos. Otro pueden ser las fechas, que son números pero tampoco son operables. Son una estructura con una forma concreta, como YYYY-MM-DD. A esto se le puede añadir también la hora, según el tipo de dato de fecha. Para pasar lista en la columna de la decha, solo contaremos con datos "Booleanos", es decir código binario. Si incorporamos un tercer dato la tabla puede fallar.

OpenRefine, un programa que hay que tener siempre encima para el periodismo de datos. Antes se llamaba Google Refine. Sirve para trabajar con datos en sucio. Lo que hace es utilizar la máquina virtual de Java para lanzar una aplicación web, donde cargas el csv y entonces ves los datos en su forma de visualización.

Volviendo a la lista, en la parte de los apellidos no hay tildes, está ordenada por orden alfabético. Lo de las tildes es porque como la programación parte del inglés y este es un idioma que no acepta acentos, la mayor parte de los formatos de datos no aceptan caracteres con tilde o la letra ñ. Luego se evolucionó con los ISO-88859, y ahora el mundo vive feliz porque lo que existe es el UTF-8 o UNICODE, donde ya caben todos los caracteres. EL UNICODE, para que quede claro, es una codificación de caracteres de los archivos de datos. 

Dentro del tipo de datos de los números, están los números decimales u otros tipos. Las cadenas de caracteres son un tipo de datos conocido como strings.

Funciones: Join () para unir texto, uppercase () para poner las cosas en mayúscula y lowercase () para poner las cosas en minúscula.
