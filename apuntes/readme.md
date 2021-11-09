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


## 22/09/2021


# Nombres de archivos y carpetas

Recordamos que en Github si creamos un archivo hemos de incluir la extensión md para que lo trate como un texto markdown y por tanto lo procese correctamente.
En Github los nombres del primer archivo se llaman README.md para que lo leas (¡léeme!) y de alguna forma como homenaje a los archivos del software que se leía en pantallas en blanco y negro donde se prefería las mayúsculas para la mejor lectura.
En vuestro caso yo optaría por nombrar tanto los archivos como las carpetas en minúsculas y separando las palabras con guiones medios, es decir: esta-es-una-carpeta y esto-es-un-archivo.md.
Hay otras formas posibles pero es importante que seáis metódicos para que siempre lo hagamos así y sepamos por tanto acceder y recuperar nuestros archivos y carpetas.
Repaso del día anterior

Después de repasar todo llegamos a que algunas personas con Mac no habían conseguido instalar XCode. A partir de ahí hemos empezado con la instalación o puesta a punto de la terminal.
Windows

# Cygwin

Se puede descargar en https://www.cygwin.com/
Emulador de la terminal POSIX en Windows
Ofrece un cojunto de herramientas y programas que emulan una distribución Linux en Windows.
Tiene desventajas conocidas: instalación, actualización, usabilidad de la instalación…
¡Atención! Una vez que lo descargáis y lo instaláis, no tiréis el instalador ya que es necesario para su actualización.
La primera vez que lo usamos descargamos lynx, un navegador en línea de comandos.
Para no tener que correr manualmente el instalador cada vez que queremos actualizar Cygwin con algún paquete/programa, usaremos apt-cyg
apt-cyg

Cygwin es una herramienta muy potente para Windows pero muy tediosa de utilizar.
apt-cyg es un gestor de paquetes de Cygwin que funciona en línea de comandos.
El nombre proviene de ser como un apt para Cygwin.
Un APT (Advanced Package Tool) es un conjunto de herramientas para manejar los paquetes –programas– de los sistemas Debian GNU/Linux. Se ha hecho muy popular su funcionamiento y otros sistemas
operativos lo han imitado porque permite:

Instalar programas.

Desinstalar programas.

Actualizar programas.

Resolver dependencias de los programas de forma automática.

Sin apt-cyg, cada vez que queremos instalar algo hay que abrir el programa de instalación de Cygwin.

Con apt-cyg conseguimos instalar o actualizar programas que usamos en Cygwin desde la propia consola de Cygwin.

Instalación de apt-cyg

Para instalarlo, tal como cuentan en su página web, usamos dos líneas de comandos:

lynx -source rawgit.com/transcode-open/apt-cyg/master/apt-cyg > apt-cyg
install apt-cyg /bin
La primera línea dice que ejecutará lynx con la opción -source para descargar el código fuente de la página rawgit.com/transcode-open/apt-cyg/master/apt-cyg y ese texto lo envía con > al archivo apt-cyg.
Lynx es un navegador en línea de comandos que se puede utilizar para esto. El próximo día probaremos con otras páginas.

En este momento y en el directorio/carpeta/ruta donde estemos, creamos un archivo con nombre apt-cyg que contiene el texto del código fuente de esa URL, que es un script para usar Cygwin e instalar programas sin correr manualmente el instalador.

Para comprobar que está hacemos un ls, un comando para listar los contenidos de la carpeta/directorio.

Si está, pasamos a la siguiente línea. Con install instalamos el archivo apt-cyg, que es un programa, en la carpeta bin, que son los programas o binarios.

Si no ha dado error será que lo tenemos. Para probarlo escribimos apt-cyg install wget, que es la instrucción para instalar el programa wget, una herramienta para descargar archivos que usa precisamente apt-cyg

# MacOSX

Terminal

La terminal es una aplicación que encontramos disponible en "Utilidades -> Terminal" pero, de un tiempo a esta parte, está capada y no se puede utilizar con todo su potencial.
Para ello requiere activar Xcode. Esto lo conseguimos por dos vías posibles. En ambos casos debemos tener cuenta de Apple.
O bien descargamos xcode, que son muchos Gb.
O bien en la página de developer de MacOSx buscamos "Command line tools for Xcode", que es menos de medio Gb.
En cualquier caso, leed bien las instrucciones para la instalación de estos enlaces y no tengáis miedo a las advertencias de Mac sobre lo que vas a hacer pues lo único que vas a hacer es usar algo que tu ordenador es capaz de tener.
Una vez tenemos Xcode, instalamos brew que es un gestor de programas para la terminal de Mac, algo así como el apt-cyg de Cygwin.
Brew

Puedes ver el proyecto en https://brew.sh/
Se trata de un gestor de programas en MacOSX.
Hay una alternativa llamada macports.org, no son incompatibles, por si alguien se anima a experimentar.
Sirven para instalar programas que se usan en la Terminal.
La instalación fácil hasta hace poco está en la página de brew.sh
Copiamos esta línea /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)" y la pegamos en la terminal.
Sin embargo esto ha cambiado sensiblemente porque MacOSX ha dejado de utilizar BASH como el dialecto que entiende la terminal y ahora utiliza ZSH. Aunque son dialectos varían en algunas cosas. En el curso usaremos Bash por lo que recomiendo hacer lo siguiente:
spirosfromlondon nos cuenta que tendremos que lanzar brew update y luego brew install bash. Comprobamos con bash --version y para que MacOSX no olvide esto, editamos el archivo ~/.bash_profile con nano, por ejemplo y añadimos esta línea: export BASH_SILENCE_DEPRECATION_WARNING=1.
nano es un editor en línea de comandos, lo veremos el próximo día.
Luego ya podemos instalar programas. Por ejemplo, wget con brew install wget.
Quizás surjan otros problemas, como este… no dudéis en comentarlos.
Si quisierais seguir con zsh y no os da problemas, genial. Aquí hablan de algunos problemas que se han encontrado.
Repaso

 Control ordenador.
 Emulador de terminal con Cygwin (W$) o activando XCode (MacOSX) para aplicaciones CLI
 Editor de textos con nano
 Sintaxis Markdown
 Control de versiones git.
 Github para repositorios de documentación y servidor web.
 Python para algunas funcionalidades.
 
 
 ## 28/09/2021
 
 
# Ley de Murphy

Disculpad el retraso, os quería hablar de la ley de Moore pero debería empezar por la Ley de Murphy.  


# Terminal

Tres comandos vamos a usar:  

-   `pwd` o *print working directory*, es decir, imprime el directorio de trabajo.
-   `ls`, sirve para listar los archivos y directorios del directorio donde estás.
-   `cd`, para cambiar de directorio.


# Jerarquía del sistema de directorios

-   Metáfora arriba/abajo en un eje de Y donde el punto 0 es la raíz del sistema operativo, representado en Unix con una `/` y en
-   Metáfora adelante/atrás en el eje de las X donde el punto 0 es la raíz del sistema operativo.
-   Metáfora entrar al directorio/salir del directorio.
-   En el mundo web además del punto 0 de la web está la URI o dirección del recurso en la red. Veámoslo con un ejemplo: `https://workforus.theguardian.com/careers/product-engineering/`  
    -   En esta URL el dominio es la raíz, en este caso `workforus.theguardian.com`
    -   El directorio de primer nivel sería `careers`.
    -   Que tendría dentro el directorio `product-engineering`
    -   Y dentro estará el archivo `index.html`
```
    workforus.theguardian.com
    └── careers
        └── product-engineering
            └── index.html
```
Voy a añadir además los directorios `img` y `js` que cuelguen de la raíz del árbol y les voy a crear un archivo dentro de cada uno:  
```
    workforus.theguardian.com
        ├── careers
        │   └── product-engineering
        │       └── index.html
        ├── img
        │   └── icon.png
        └── js
            └── lib.js
```
Si estoy en `index.html` y quiero referirme a la imagen `icon.png` que está en el directorio de las imágenes, puedo hacerlo con la ruta relativa o la ruta absoluta:  

-   Ruta relativa: según en el sitio en el que me encuentro, es decir, en `index.html`, luego tengo que subir un directorio hasta `careers`, otro hasta la raíz `workforus.theguardian.com`, y luego bajar al directorio `img`. Eso se representa así: `../../img/icon.png`. Es decir, con `../` se sube un directorio.
-   Ruta absoluta: desde la raíz. Dado que la raíz está representada por una `/`, hacemos: `/img/icon.png`
-   Ruta URI: dado que es un recurso disponible en la red de Internet, también podría tener la ruta `https://workfocus.theguardian.com/img/icon.png`. Cuando se ponen rutas URI se puede quitar la parte del protocolo, lo cual se hace por si en algún caso tiene problemas con uno u otro, quedando así: `//workfocus.theguardian.com/img/icon.png`

El porqué poner uno u otro depende de cómo esté montada la web. Suele ser mejor poner rutas absolutas si crees que las relativas pueden variar, pero también podrían cambiar potencialmente las absolutas.  


# Git


## Instalación

Instalamos git en el ordenador.  

-   En cygwin, `apt-cyg install git`
-   En linux, `sudo apt install git`
-   En mac, `brew install git`


## Problemas en Windows: el Antivirus

-   Se han detectado problemas o bien al instalar git o bien al clonar el repositorio luego.
-   Cuando estéis con estas cosas desactivar el antivirus o permitidle una excepción de cygwin porque si no no funciona bien.


# Mundo web

-   Por cierto, antes de hacer lo de Github&#x2026; ¿habéis visto su página? ¿Os recuerda a algo? ¿No?
-   Ahora veamos la de Twitter&#x2026; ¿se parecen?
-   Resulta que la web de Github está diseñada con el framework Bootstrap  <https://getbootstrap.com/>
-   Bootstrap es un framework de desarrollo web que liberó Twitter cuando rediseñó su página
-   Muchas de las páginas del mundo están basadas en Bootstrap. En algunas se nota más que en otras.
-   Aunque Bootstrap tiene iconos, hay otro proyecto que también se usa, [Fontawesome](https://fontawesome.com/v5.15/icons?d=gallery&p=2&m=free)


# The Guardian

Vaya sorpresa me he llevado cuando el clásico "We Are Hiring!" del código fuente de [The Guardian](https://www.theguardian.com/international):  

![img](/img/the-guardian-source.png "We Are Hiring!")  

Ha sido sustituida por:  

![img](/img/the-guardian-200.png "G: 200 Anniversary The Guardian")  

Resulta que este año se celebra el bicentenario del periódico:  

![img](/img/theguardian-frontpage.jpeg "200 Anniversary The Guardian")  


# Github

-   Vamos a github y copiamos la dirección del repositorio, por ejemplo: `https://github.com/Pontedatos/uc3m-periodismo-datos.git`
-   Lo clonamos en el directorio donde estamos con `git clone https://github.com/Pontedatos/uc3m-periodismo-datos.git`.
-   Esto significa que creara una carpeta/directorio en nuestro espacio con el nombre `uc3m-periodismo-datos` con el contenido de ese repositorio remoto.
-   Si añadimos al final, separado con un espacio, un nombre, llamará a la carpeta como queramos. Por ejemplo, `git clone https://github.com/Pontedatos/uc3m-periodismo-datos.git periodismodatos`, la carpeta con el contenido será `periodismodatos`.
-   Para comprobar que lo hemos descargado/clonado, lanzamos `ls`, se tendrá que ver el nombre del directorio tal como lo hemos llamado.
-   Ahora vamos a entrar/cambiar a ese directorio con el comando `cd`, de *change directory*, que lo podemos recordar por "Cambiar de Directorio". Así, `cd uc3m-periodismo-datos` nos lleva a ese directorio.
-   Lo listamos con `ls` para comprobar su contenido.
-   Si en vez de `ls` lanzamos las opciones `ls -la` vemos que tiene un directorio de nombre `.git` que es donde está toda la configuración de este repositorio git.
-   Es decir, esta carpeta también es un repositorio git local.
-   Si queremos saber a dónde apunta hacemos `git remote -v` y nos dice la URL de donde hacer "fetch", de donde descargar datos, y a donde hacer "push", donde subir datos.
-   Mañana practicaremos con esto.
-   Para volver al directorio anterior tenemos que subir o retroceder un directorio, lo hacemos con `cd ../`


# Pendientes

-   [ ] Ley de Moore
-   [ ] Entidades HTML
-   [ ] Caracteres reservados
-   [ ] `ls -la`
-   [ ] xcode
-   [ ] Datos abiertos: 5 estrellas <https://5stardata.info/en/>
-   [ ] Journalism in the Age of Data: <http://datajournalism.stanford.edu/>
-   

## 05/10/2021


# Ruido-silencio


# Compeñerismo


# Pandora Papers


# Variables de entorno


# echo


# ls


# mkdir


# cat


# Estructura de ficheros


# Rutas


# ToDo

-   touch
-   prompt
-   git


## 06/10/2021



# The mother of all demos

![img](/img/1968-demo-poster.jpg "1968 a research center for augmenting human intellect")  

-   Es como se conoce a la presentación realizada por Douglas Engelbart en los Xerox Labs de Palo Alto en 1968.
-   Los Xerox Labs dieron forma a las interfaces gráficas que luego popularizaron Mac o Windows.
-   Pero este nombre es posterior, de 1994.
-   Entonces se llamó "Un centro de investigación para aumentar el intelecto humano". Formaba parte de la conferencia de Fall Joint Computer en el Brooks Hall en San Francisco.
-   El proyecto fue resultado del trabajo realizado en el Augmentation Research Center del Instituto de Investigación de Stanford.
-   En esta [demostración de las tecnologías experimentales](https://es.wikipedia.org/wiki/The_Mother_of_All_Demos) se presentan varios hitos:  
    -   Un sistema operativo denominado NLS
    -   Uno de los primeros ratones.
    -   Sistema de videoconferencia
    -   Sistema de teleconferencia
    -   Hipertexto
    -   Procesamiento de textos
    -   Hipermedia
    -   Archivo de vinculación dinámica
    -   Control de revisiones (versiones)
    -   Editor en tiempo real colaborativo


## Enlaces

-   Vídeo resumen que visionamos: <https://www.youtube.com/watch?v=B6rKUf9DWRI>
-   Vídeo completo: <https://www.youtube.com/watch?v=yJDv-zdhzMY>
-   Doug Engelbart Institute: <https://dougengelbart.org/content/view/209/>


## Prueba

-   Contrasta el uso que haces del ordenador con el uso que proponía Doug y explícalo.
-   Puedes ayudarte de una tabla.
-   ¿Qué cosas permanecen y qué ha cambiado?


# Entidades HTML

Una persona quería mostrar una flecha en Markdown tal como se le mostraba en su M$Word. Es decir, en este editor si escribes `->` se convierte en el carácter de una flecha que apunta a la derecha.  
En Markdown se pueden incluir estos caracteres pero para ello hemos de saber su codificación HTML. Recordad que **allí donde Markdown lo hace HTML**.  

En HTML estos caracteres que no son los comunes se tienen que representar con un código hexadecimal. Tened en cuenta que la codificación [ASCII](https://es.wikipedia.org/wiki/ASCII) (American Standard Codification for Information Exchange, codificación americana estándar para el intercambio de información) cubría solo los caracteres habituales del alfabeto inglés. Por tanto, ni la `ñ` ni las tildes están ahí. Para representar estos caracteres se puede hace a través de entidades HTML o bien de código hexadecimal. Se pueden usar ambos pero las entidades HTML se han hecho para que sean más fáciles de recordar. Eso sí, no cubren **todos** los caracteres y en el resto de casos, como el de la flecha, hay que poner el código hexadecimal.  

Las entidades HTML son un conjunto de caracteres o `string` que empiezan por un ampersand `&` y terminan con un `;` punto y coma. Por ejemplo, el carácter `á` se escribe `&aacute;`; el carácter `é` se escribe `&eacute;`, etc;  

Las entidades HTML también nos sirven para conocer que en todos los lenguajes informáticos existen los **caracteres reservados**, es decir, caracteres que no podemos usar tal cual porque el lenguaje los entiende de una manera especial. Como en HTML el carácter de `<` menor que es el inicio de una **etiqueta**, si queremos poner una expresión matemática del tipo `4<6`, cuatro es menor que 6, habrá que poner la entidad de ese carácter: `4&lt;6`, donde `&lt;` corresponde al carácter `<` y donde `lt` viene de *lower than*.  

Esto ocurre con el propio carácter de ampersand. Si queremos usarlo y que HTML no lo entienda como el inicio de una entidad HTML, hemos de poner la entidad. Así, la empresa `Ernest&Young` se pondría en HTML como `Ernest&amp;Young`, donde `amp` proviene de ampersand.  


## Enlaces

-   Página de ayuda de Mozilla: <https://developer.mozilla.org/es/docs/Glossary/Entity>
-   Lista completa de entidades: <https://html.spec.whatwg.org/multipage/named-characters.html#named-character-references>


## Prueba

Entonces, ¿cuál es la entidad HTML para la flecha que quería representar nuestra compañera?  


# Escapar caracteres en la terminal *Shell*

-   Como cualquier otro lenguaje informático, los dialectos de la `Shell` (`Bash` o `zsh`, que son los que usamos) tienen también caracteres reservados que habría que "escapar" para que no los entienda como tal si los queremos poner de determinada manera.
-   Algunos de estos caracteres los hemos visto:  
    -   **`>`:** para enviar la salida de un comando (STDOUT) a un archivo que crea en el acto o sobreescribe si ya existiera.
    -   **`>>`:** para enviar la salida de un comando (STDOUT) al final de un archivo si existe, y si no lo crea.
    -   **`|`:** para enviar la salida de un comando (STDOUT) a un comando (como STDIN) para que lo interprete.
-   Así, por ejemplo, si queremos decirle a `echo` que `6 > 3`, seis es mayor que tres, debemos escapar el carácter porque si no lo que hará `echo` será decir `6` y esa salida estándar STDOUT la enviará a un archivo de nombre 3 que contendrá 6. Podéis probarlo.
-   Para escaparlo podemos hacer dos cosas (siempre se pueden hacer varias cosas).  
    -   Una es propia del comando `echo`, y es entrecomillar todo el texto para que entienda que todo es parte de la cadena de caracteres o `string`: `echo "6 > 3"`.
    -   Otra es escapar solo el carácter, y eso en la shell se hace con el carácter `\`: `echo 6 \> 3`


## Enlaces

-   <https://www.shellscript.sh/escape.html>


## Prueba

Dado el significado que tienen las comillas para el comando `echo`, cómo harías para que devolviera una frase como: La Justicia europea considera "discriminatorio" el sistema de financiación del bono social de las eléctricas (Fuente: <https://www.eldiario.es/economia/justicia-europea-considera-discriminatorio-sistema-financiacion-bono-social-electricas_1_8394400.html>)  


# Cambiar la home en Cygwin

-   Queremos cambiar la home de Cygwin.
-   Este es un juego divertido que la gente de Mac o GNU/Linux no necesita hacer, en principio.
-   Recordemos que cuando digo `home` me refiero al directorio del sistema de archivos donde se encuentran mis archivos personales, es decir, lo que en un Windows o Mac es mi espacio del ordenador y a partir de ahí cuelgan las carpetas de `Escritorio`, `Descargas`, etc.
-   Por defecto, la **home** del usuarix de Cygwin es el directorio de instalación del programa que monta una estructura Unix con ruta `/home/nombre-usuarix/`.
-   Esto lo vemos cuando arrancamos el programa y escribimos (le preguntamos) `pwd` (imprime el directorio de trabajo) y devuelve una ruta que es esa.
-   Para ver el árbol de directorios de Cygwin o Mac o Linux, podéis hacer `tree -L 1 /`. El comando `tree` muestra el árbol de directorios y archivos. Con la opción `-L 1` (`L` de *level* o nivel) muestra un nivel del árbol desde el punto (el argumento `/`) que le hemos dicho, en este caso la raíz, principio o núcleo del árbol de directorio representado por una `/` barra.
-   Cygwin instala, por defecto, el espacio de usuario en una parte del propio programa, en `/home/`. Lo que queremos hacer es que tenga como `home` el espacio de mi usuario de Windows.
-   Para disfrutar de `Cygwin` y acceder al espacio de quien usa el ordenador de Windows, una opción es [modificar](http://stackoverflow.com/questions/1494658/how-can-i-change-my-cygwin-home-folder-after-installation%0A) la variable `db_home` en `/etc/nsswitch.conf` con nuestro editor `nano`.
-   Pero antes&#x2026;


## Antes de cambiar la `home`

En la `home` de Unix se crean unos archivos por defecto:  

-   `.bashrc`, donde se encuentra la configuración de `BASH`.
-   `.bash_profile`, donde se encuentra la información del perfil de lxs usuarixs de `BASH`.
-   `.bash_history`, donde se almacenan los comandos que utilizamos.

Tanto si estos archivos contienen información útil como si no, antes de cambiar la **home**, cópialos al directorio que va a ser el nuevo directorio de trabajo, es decir:  

    cp .bash* /cygdrive/c/Documents and Settings/usuarix/.


## ¿Quién soy yo?, ¿cuál es mi usuarix?

-   Hay un comando que nos lo dice, `whoami`.
-   Dado que Cygwin ha copiado el nombre de Windows, esto funciona también aquí.

    whoami


## Editemos nsswitch.conf

-   A la hora de escribid nombres de archivos, de directorios o rutas completas, recordad que la tecla de tabular es vuestra amiga :smiley-cat:
-   Entonces, escribimos `nano /etc/nsswitch.conf`
-   Y al final del archivo, abajo, escribimos `db_home: windows` o bien `db_home: /%H`.
-   Guardamos y salimos (o salimos y guardamos :recycle:)


## ¿Hashtag? ¿Qué es la almohadilla?

-   Tened en cuenta que en los archivos de configuración de la `Shell`, la almohadilla `#` que aparece al principio de línea significa que la línea está comentada, es decir, que no la va a leer el programa que quiera leerla para hacer algo.
-   En Markdown el mismo carácter es el equivalente del elemento `h1` de HTML o "encabezamiento de primer nivel".
-   Así que os pueden quedar varias líneas comentadas, incluso contad lo que habéis hecho en una línea comentada, para que cuando volváis a este archivo sepáis por qué esta línea es así:  
    
        # Ahora modifico la línea de la variable db_home


## ¿No fue posible?

Si a alguien no le funciona, puede proponer este otro método que proponen en esta [página](http://stackoverflow.com/questions/225764/safely-change-home-directory):  

    mkpasswd -l -p "$(cygpath -H)" > /etc/passwd


# Listar archivos, opciones

-   **`ls`:** listamos archivos y directorios
-   **`ls -a`:** listamos archivos y directorios ocultos
-   **`ls -la`:** listamos archivos y directorios ocultos con detalle.
-   Hay un montón de opciones más.


# Copiar archivos y/o directorios

-   Para copiar está el comando `cp`
-   Su comportamiento es `cp OPCIONES ruta/s-origen ruta-destino`. Es decir, admite copia una cosa o varias a un destino final.
-   Tened en cuenta siempre eso que os decía que cuando ponemos el nombre de los archivos o las carpetas en realidad estamos poniendo su ruta en el sistema de ficheros.
-   Si copiamos un directorio y tiene contenido hemos de poner la opción `-r` que significa "copia recursiva".


# Mover archivos y/o directorios

-   Para mover archivos, es decir, cortar y pegar algo en un destino determinado, está el comando `mv`.
-   Su comportamiento es `mv OPCIONES ruta/s-origen ruta-destino`. Admite, también, mover una o varias cosas a un destino final.
-   Se puede usar también para renombrar archivos o carpetas. Es decir, si hacemos `mv hola.txt adios.txt` lo que hacemos es mover el archivo `hola.txt` al archivo `adios.txt`, es decir, borrar `hola.txt` y crea `adios.txt`; y si existiera, lo sobreescribe.


# Wildcards o comodines

-   A la hora de listar, copiar, mover y otras operaciones se pueden usar las `wildcards` o comodines.
-   Imaginad que tenéis una carpeta en vuestro Escritorio de nombre `data` y dentro de ella tenéis archivos `csv`, `json` y `xls`, todos en la misma carpeta. Y queréis organizar eso un poco por tipo de archivo.
-   Entonces creamos unas carpetas que se llamarán `csv`, `json` y `xls` dentro de `data`.
-   Nos situamos en el directorio `data` con el comando `cd`: `cd ~/Escritorio/data`
-   Creamos las carpetas con `mkdir`: `mkdir csv json xls`.
-   Movemos los archivos con mv: `mv *.json json/`, y luego con los otros dos tipos de archivos.


## Enlaces

-   Wildcards: <https://www.shellscript.sh/wildcards.html>. Forma parte de una guía sobre programación en la Shell que no tiene mala pinta.


# Make a better prompt

Para cuando usemos git el próximo día:  
<https://github.com/git/git/blob/master/contrib/completion/git-prompt.sh>  


# Mac

No hace falta instalar todo XCode sino que hay que instalar Command Line Tools for XCode. La versión dependerá de la versión que tengáis  

    xcode --install


# Almohadilla

<https://es.wikipedia.org/wiki/Almohadilla>


## 13/10/2021

<img src="![img](https://www.retroavangarda.com/wp-content/uploads/2016/03/okladka-london-calling-simonon-clash-elvis-presley-e1460242755720.jpg2) alt="Portada de London Calling de The Clash homenaje a la portada del primer álbum de Elvis Presley">  


# ¿A qué hora comienzan las clases? ¿A qué huelen las nubes?

-   Las clases comienzan a las 14:30.
-   Voy a intentar empezar todas las sesiones con un vídeo corto, que va a empezar a las 14:30 y no durará, normalmente, más de 10 minutos.
-   Así se cubren esos 5 minutos de cortesía.
-   Os invito a que veáis algún vídeo también si yo no llegara en esos minutos. Solo hay que buscar "data journalism" o "periodismo datos" en Youtube.


# Data Journalism is the New Punk

-   Así definió Simon Rogers al periodismo de datos en el TEDxPanthéonSorbonne en noviembre de 2012 <https://www.youtube.com/watch?v=h2zbvmXskSE>
-   Define el punk como algo muy importante para la juventud porque les permitía formar una banda solo con tener una guitarra y con tres acordes se podía hacer una canción.
-   Lo que fue importante para la juventud de los 1970' puede representar ahora los datos: tienes tres conjuntos de datos y ya puedes hacer una historia interesante.
-   Rogers quería escribir y ser periodista cuando tenía 6 años. Pero tenía miedo a las matemáticas.
-   Sin embargo en el periodismo de datos necesitas tener conocimientos matemáticos, técnicos.
-   Hay portales de datos abiertos, proyectos de liberación de datos, filtraciones como Wikileaks&#x2026;
-   También herramientas libres o abiertas como Datawrapper para crear visualizaciones.
-   Con UK Riots se volvió a revisar el inicio del periodismo de precisión de Philip Meyer y sus Detroit Riots.
-   Open Journalism
-   Joe Strummer: people can do anything.


## Enlaces

-   Página de Simon Rogers: <https://simonrogers.net>
-   Cosas que hace en Google <https://trends.google.com/trends/story/US_cu_6fXtAFIBAABWdM_en>
-   Data Journalism Podcast: <https://simonrogers.net/2021/04/26/introducing-the-data-journalism-podcast/>


# lolcat

-   Si disponemos del comando `man`, podemos usarlo para saber qué es `lolcat`:
-   NAME, lolcat: "rainbow coloring effect for text console display"
-   SYNOPSIS: `lolcat [options] [files] ...` (recuerda la estructura `comando opciones argumentos`. En este comando se pueden poner más de un argumento (más de un archivo) en la misma línea.
-   DESCRIPTION: "lolcat  is  a program that concatenates files, or standard input, to standard output (like the generic cat), and adds rainbow coloring to it."
-   Así que es como `cat` pero le da un colorido de arcoiris a la salida.


## Instalación

-   En Mac haremos `brew install lolcat`
-   En Cygwin es un poco más complicado porque no está empaquetado para Cygwin así que podemos usar, por ejemplo, la librería `lolcat` de `ruby`.


## ¿Ruby?

-   Sin entrar mucho en detalles, `ruby` es un lenguaje de programación moderno que pretendía lo que mucho pretenden


## Ruby can't fail

-   Nota: el nombre sigue la línea del London Calling de los Clash y su canción "Rudy can't fail" <https://www.youtube.com/watch?v=uEK9oK02D1M>
-   No siempre se acierta sobre el terreno y en caliente, pero a veces hay que tomar decisiones.
-   Parece ser que no somos lxs primerxs que experimentamos ciertos problemas con Ruby en Cygwin así que quien tiene problemas con `lolcat` puede probar esto:  
    -   <https://itectec.com/superuser/windows-gem-not-working-in-cygwin/>
    -   Run the Cygwin setup, and choose Ruby, under the Ruby category. Also make sure that you've installed the gcc compiler and GNU make, under the Devel category, so that the gems can build the native extensions. <https://stackoverflow.com/questions/14376138/how-to-fix-gem-install-gtk2-in-cygwin-ruby-on-windows>
    -   install curl, git, nano, openssh, openssl, unzip, util-linux, vim, wget. <https://gist.github.com/ahsankhatri/260c58929962a01bf9e26ef660c832d0>
    -   Descargar ruby <https://rubyinstaller.org/downloads/> y añadirlo al `PATH`: `/cygdrive/c/Ruby22/bin`
    -   Edit ~/.bash\_profile or ~/.profile, Add alias gem=gem.bat, Install Mailcatcher  gem install mailcatcher, Now whenever you install any package from gems you need to add alias in ~/.bash\_profile in order to run in cygwin OR you can directly batch file with gem.bat -v, e.g. add alias mailcatcher=mailcatcher.bat in ~/.bash\_profile


# Enlaces

-   Herramientas curiosas de la línea de comandos, <https://infotics.es/articulo/herramientas-curiosas-en-la-linea-de-comandos/>, las veremos el próximo día.


# Pruebas

-   Empieza de forma simple, con el comando `echo` y manda la salida a `lolcat`
-   Baja el código fuente de una página y pásale `lolcat`
-   Guarda alguno de estos resultados y míralo con `nano`


## 19/10/2021


# Dialectos de la shell

`cat /etc/shells`  


# Google dorks u operadores de buscadores

Al igual que en la terminal se utilizan operadores, en los buscadores se ha convenido en utilizar algunas palabras clave de una forma especial para restringir la búsqueda  

-   <https://ahrefs.com/blog/es/operadores-de-busqueda-avanzada-de-google/>
-   <https://moz.com/learn/seo/search-operators>
-   <https://osintcurio.us/2019/12/20/google-dorks/>


# Fancy command line

Tomando como base este artículo: <https://infotics.es/articulo/herramientas-curiosas-en-la-linea-de-comandos/>  
Utilzamos `sl` y `lolcat`  


# neofetch

<https://github.com/dylanaraps/neofetch>  


# Admin en Cygwin

Algunas utilidades de administración en Cygwin:  

-   `uname -a`
-   `cygcheck -c python`


# WSL

Os recuerdo esto que dijimos el otro día: WSL (Windows con Linux) <https://docs.microsoft.com/en-us/windows/wsl/about>  


# Pruebas

-   ¿Qué otros comandos o expresiones le pasarías a `lolcat`?
-   Pon ejemplos de uso de los operadores de buscadores y sus resultados



## 20/10/2021


# Git y Github


## El repositorio de pontedatos

-   Ya tenemos un repositorio en la organización a la que pertenecemos como clase, <https://github.com/pontedatos/uc3m-periodismo-datos>
-   Lo que vamos a hacer es o bien descargarlo si no lo hemos hecho o bien actualizarlo si ya lo habíamos descargado.
-   Cuando digo "descargarlo" en realidad digo "clonarlo", es decir, voy a la carpeta de mi elección con el comando `cd` y escribo `git clone https://github.com/pontedatos/uc3m-periodismo-datos.git`.
-   Esto creará una carpeta por debajo de donde me encuentro con el nombre `uc3m-periodismo-datos`. Esa carpeta es un repositorio git en nuestro ordenador, en `localhost`, que tiene el mismo contenido que el de la dirección desde donde me lo he clonado.
-   Si ya hubiera hecho esto alguna vez tendría que ponerme dentro de la carpeta y actualizar con `git pull`.


## Nuestro repositorio

-   Es probable que tengáis un repositorio vuestro cuyos contenidos solo estén en github.
-   Vamos a descargarnos los datos de la misma manera que antes.
-   Nos situamos en la carpeta elegida y clonamos con `git clone` seguido de la dirección de nuestro repositorio git en github.
-   Luego con `cd` nos situamos dentro del repositorio.
-   Ahora con `nano` o nuestro editor favorito cambiamos algo, guardamos, cerramos y seguimos tres pasos para actualizar los cambios en github:  
    -   `git add nombre-archivo-cambiado`
    -   `git commit -m "comentario del cambio"`
    -   `git push origin main`
-   Si al dar `git push` da error consultamos el error por el foro.


## No tenemos un repositorio

-   Si no tuviéramos un repositorio podríamos crear uno nuevo.
-   Primero creamos una carpeta con el nombre que queramos aunque lo suyo es que sea el nombre del repositorio.
-   Luego con `cd`  nos situamos dentro de la carpeta.
-   Y entonces creamos un repositorio en Github y, cuando llegue el caso, seguimos en la terminal estos pasos que indican:
```bash
echo "# Proyecto de ..." >> README.md
git init
git add README.md
git commit -m "primer commit"
git remote add origin https://github.com/cuenta/nombre-repositorio
git push -u origin main
```

## No nos reconoce

-   Comenta una compañera que tiene problemas con `git` porque en el paso `git commit -m` le sale un aviso que no logra interpretar.
-   Una recomendación previa y para que lo tengáis en cuenta: conviene leer los mensajes que da el software e intentar interpretarlos adecuadamente. A veces nos "resuelven" el problema. Entiendo que "desconciertan" pero también hay que acostumbrarse a leerlos, a buscar soluciones e intentar resolver problemas/inconvenientes que surjan. En este caso, además, la compañera ha compartido una captura de pantalla del aviso y de esa manera ha sido fácil resolverlo, os lo cuento.
-   Spoiler: lo que dice se resuelve en esta sección de este manual que os enlacé con mis notas de git y github:

<https://flowsta.github.io/github/#outline-container-org19f011c>  

-   Os lo explico paso a paso. La primera vez que usamos en el ordenador `git` de la manera que os propuse, es decir, no desde la interfaz de Github sino desde vuestro ordenador, a través de la terminal, tenemos que identificarnos.
-   En este caso lo que dice es `Author identity unknown`, es decir, se desconoce la identidad de quién eres para `git`, para firmar ese `commit` y luego subirlo al servidor que vas a utilizar.
-   Y además añade `*** Por favor, cuéntame quién eres`
-   A continuación dice que corras (que ejecutes) dos líneas de instrucciones en la terminal. Tened en cuenta que cuando salen varias líneas en este tipo de avisos, como cuando instalamos `apt-cyg`, no se copian las dos líneas juntas sino que se pone primero una, se ejecuta, y luego la otra.
-   En este caso, lo que dice primero es que les digas cuál es tu dirección de correo electrónico. En este caso, como usamos como servidor externo a Github, ponemos el correo electrónico con el que nos hemos registrado en Github: `git config --global user.email "tu-email-en-github"`
-   En esta instrucción, la opción `--global` indica a `git` que siempre vas a usarlo en la terminal con este mismo `user.email`. Por tanto, no tendrás que volver a configurar esto.
-   La siguiente línea solicita que le digas cuál el nombre de tu cuenta `git config --global user.name "cuenta-en-github"`
-   A partir de ahí podréis seguir hasta el próximo desafío.


## :new: Tokens

-   Para anticiparos el próximo "desafío" con que os vais a encontrar os cuento que Github cambió hace poco la forma de relacionarse con Github y ahora hay que generar una clave para subir los contenidos, para hacer el `git push`.
-   Antes había que poner la contraseña de github, ahora hay que generar una clave.
-   Esto se hace yendo a <https://github.com/settings/tokens> y generando un nuevo `token`.
-   Hay que darle un nombre, elegir una fecha de caducidad (puede ser "nunca" aunque, ya que estáis aprendiendo, mejor ponerle una caducidad para que tengáis que volver a ese paso en algún momento) y seleccionar un ámbito de actuación o "scopes".
-   Para lo que vamos a hacer basta con que marquéis "repo" y los que cuelgan de él:  
    -   repo
    -   repo:status
    -   repo\_deployment
    -   public\_repo
    -   repo:invite
    -   security\_events
-   Una vez marcado esto y creado el token os genera un "hash", un código que conviene que copiéis en alguna parte &#x2013;:warning: cuidado: no en los apuntes públicos&#x2013; y que será el que tengáis que poner cuando hagáis `git push` en vez de la contraseña.


# Enlaces

-   Viejo manual de git y Github: <https://flowsta.github.io/github/>
-   Recordad mis notas sobre Markdown en <https://flowsta.github.io/markdown>
-   Editores para Markdown:  
    -   MarkDownEditor, W$, <https://github.com/chenguanzhou/MarkDownEditor>
    -   Abricotine, W$-OSX-GX, <https://abricotine.brrd.fr/>
    -   MarkText, W$-OSX-GX, <https://marktext.app/>
    -   Ghostwriter, W$-OSX-GX, <https://wereturtle.github.io/ghostwriter/>
    -   Atom, GX, <https://atom.io/>
    -   VSCodium, W$-OSX-GX, <https://vscodium.com/>
    -   Remarkable, W$-GX, <https://remarkableapp.github.io/>
    -   Haroopad, W$-OSX-GX, <http://pad.haroopress.com/user.html>
    -   Emacs, W$-OSX-GX, <https://www.gnu.org/software/emacs/>
    -   nano, CLI, <https://www.nano-editor.org/>
-   Data Science at the Command Line <https://www.datascienceatthecommandline.com/>


# Pruebas


## git

-   Tal como hemos hecho con git y Github, clona tu repositorio en el lugar que consideres adecuado y coméntalo.
-   Edita alguno de los archivos con tu editor favorito, por ejemplo, `nano`. Si no te acuerdas puedes preguntar por el foro y/o bien probar algún otro editor de los mencionados anteriormente.
-   Actualiza el repositorio remoto.


## Comentario de visualización

-   Según dijimos en la primera sesión, realiza un comentario de una o varias visualizaciones de datos y/o infografías que queráis y justificar las respuestas y la elección.


# Recordatorios

-   Se puede solicitar tutoría para tratar temas del curso.
-   Quien tiene problemas con ruby puede probar con la vía propuesta en la sesión anterior y contar cómo ha ido.
-   Quien no tenga Cygwin configurado que repase los apuntes. Conviene tener instalado `apt-cyg` y el cambio de la `home`.
-   Quien elija `nano` puede visitar su página web por si encuentra información útil: <https://www.nano-editor.org/>.


# ToDo

-   Estilo de la terminal
-   Estilo de PS1
-   Resaltado de sintaxis en `nano`.
-   [Atajos](https://www.nano-editor.org/dist/latest/cheatsheet.html) en `nano`
-   Personalización en `nano`

## 02/11/2021

# Para hacer un trabajo en periodismo de datos

- Markdown: apuntes en github

- Pandoc: conversor universal de textos

- Bootstrap: herramientas de código abierto para diseño de páginas web y aplicaciones

- Datawrapper: para la visualización, si nos sentimos cómodos, podemos hacer un html con o sin estilo.

Control+D para salir de la terminal o salir de la "consola" de los comandos (cuando pones solo "lolcat" en la terminal, para volver a la normalidad tienes que poner control+d)

## 09/11/2021

Para enlazar una captura de pantalla, revisar rutas relativas y rutas absolutas.
