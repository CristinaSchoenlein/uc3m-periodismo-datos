
# Examen teórico Cristina Schoenlein
## Preguntas
1. *¿Qué es el periodismo de datos?*
El periodismo de datos es una disciplina periodística que consiste en recabar a analizar grandes cantidades de datos e información y poder clasificar, analizar y concluir en base a una filtración y un estudio de estos datos, todo ello mediante un software especializado. Del trabajo del periodismo de datos podrán derivarse visualizaciones de datos con diferentes técnicas y hacer comprensibles unos datos inabarcables de otra manera. El periodismo de datos moderno nace entre 2006 y 2008, propiciado por tres aspectos fundamentales: la abundancia de software de código abierto, la aparición de HTML5 y Open Data. Fundamentalmente hay tres áreas implicadas  en el periodismo de datos: el periodismo (investigación), los datos (registros electrónicos tratados por el ordenador) y la visualización de datos (tanto el producto final como las etapas de análisis y filtración de la información)

Hay que destacar, sin duda, la aparición del periodismo de precisión en EEUU como antecedente del periodismo de datos actual. Fue Philip Meyer quien creó en 1993 un libro homónimo donde describía esta forma de investigación cuando trató este periodismo que utilizaba el ordenador y los datos como herramienta fundamental. La terminología ha causado cierta polémica porque Meyer lo utilizó en un primer momento para diferenciar su propuesta periodística con la del estilo de Truman Capote y el New Journalism.

4. *¿Qué medio de comunicación inglés es fundamental en el periodismo y la visualización de datos?*
El medio británico The Guardian es un medio clave en la apuesta por el periodismo y la visualización de datos. Un proyecto innovador en ese sentido llevado a cabo por el medio ha sido Swarmize, que ha recibido la financiación de la Fundación Knight News Challenge. Esta plataforma pretende mejorar y facilitar la recopilación de datos, su análisis y su distribución.

6. *Cuál es la diferencia entre Internet y la Web. Razona la respuesta.*
Internet es una red de redes que funciona gracias a los protocolos TCP/IP. Es una red de ordenadores distribuiodos por todo el mundo conectados entre sí. TCP corresponde a Transmission Control Protocol, e IP a Internet Protocol, y forman los protocolos básicos de Internet.

La World Wide Web, por el contrario, es un sistema dentro de la red de Internet que comunica información que se comparte globalmente, un espacio de compartimentos relacionados entre sí de forma virtual y que funciona a su vez como una base de servidores. No deja de ser un servicio que se presta en Internet, y ahí radica su diferencia fundamental. Para el funcionamiento de la World Wide Web es necesaria la existencia de Internet.

12. *Elige una URL de una noticia de un medio de comunicación y explícala tal como hicimos en clase.*
Para entender la URL de la noticia elegida, es necesario dividir cada una de sus partes. 
“https://” : “http” es el protocolo utilizado para diseñar e integrar el software de las aplicaciones, en este caso, a http se le añade un s, que indica que el sitio web es seguro. “://” diferencia el protocolo del dominio.
“elpais.com” es el dominio de la URL, se trata en este caso del top level domain, o dominio de primer nivel, de la página, que se separa del resto de la estructura mediante el símbolo “/”
“/educacion/2022-01-19/los-protocolos-contra-el-suicidio-entran-en-la-escuela-los-padres-no-saben-lo-que-pasa-en-el-cuerpo-de-sus-hijos.html” : esta ruta diferenciada por el símbolo “/” indica la estructura fr las carpetas del servidor web y se lee de derecha a izquierda por orden de importancia. Se entiende, de esta manera, que la noticia en formato html “los-protocolos-contra-el-suicidio-entran-en-la-escuela-los-padres-no-saben-lo-que-pasa-en-el-cuerpo-de-sus-hijos.html” se inserta dentro de la carpeta “2022-01-19” y que esta carpeta está alojada en la sección “educacion” del top level domain.

13. *¿Qué significa el funcionamiento "cliente-servidor"?*
Es un modelo de aplicación en el que las tareas se reparten entre los proveedores de recursos o servicios, los servidores, y los clientes, que son los que demandan cierta información. Un cliente genera una serie de peticiones a un servidor que le da la respuesta. Se trata de una red de comunicaciones que conecta los servidores con los clientes, los servidores ofrecen a los clientes la respuesta de los recursos y aplicaciones y los clientes demandan lo que requieren en cada momento. 

20. *¿Qué es nano?*
GNU Nano es un editor en línea de comandos para crear y modificar archivos en la terminal. Sus opciones son, entre otras, realizar búsquedas y reemplazos interactivos, hacer y deshacer acciones, desplazarse por líneas, en lugar del clásico desplazamiento por pantalla, el autosangrado y el coloreado de sintaxis y el bloqueo y autoguardado de archivos. Se trata de una herramienta muy útil y que ofrece muchas ventajas frente a otros editores y puede ejecutarse desde la propia terminal.

23. *¿Qué son git y Github?*
Git es un software de control de versiones, diseñado por el creador de KernelLinux, Linus Torvalds para el trabajo colaborativo y distribuido, que se enfoca sobre todo en el mantenimiento de versiones de aplicaciones. Pretende registrar cada uno de los cambios de los archivos y coordinar el trabajo sobre archivos compartidos. Es muy popular para los proyectos de periodismo y visualización de datos.
Githum, por su parte, parte de Git porque utiliza su sistema de control de versiones, y es un portal o repositorio online que permite gestionar proyectos y controlar versiones de código de forma gratuita. Los desarrolladores suelen alojar en la plataforma sus trabajos y permite que todos los usuarios que cooperen con ellos para su trabajo. SU objetivo es alojar tu repositorio de código y permitir el trabajo en equipo dentro de un mismo proyecto. 

25. *Si quisieras ver la web theguardian.com, ¿cómo lo harías desde la línea de comandos?*
Si solo se quisiera visualizar la web desde la línea de comandos habría que seguir una serie de pasos. Para empezar, obtener la URL de la página web de The Guardian, en este caso https://www.theguardian.com. Una vez se tiene la URL, se debe copiar. El siguiente paso sería abrir la Shell de tu ordenador, y utilizar el comando “lynx” seguido por la URL. De esta manera podrás visualizar la página web desde tu terminal. Si quisieras ver el código de la página, tendrías que utilizar el mismo código, “lynx” pero añadirle la opción “-source” seguida una vez más del URL. Así obtendrías en pantalla la visión de la página en el lenguaje que tenga, en este caso HTML.

28. *¿Cómo verías las variable de entorno de tu shell "PATH"? Escribe su valor también.*
Utilizaría el comando env para ver las variables de entorno. Para ver su valor, utilizaría echo $PATH, que en mi caso es /usr/local/bin /usr/bin /bin /usr/sbin /sbin /Library/Apple/usr/bin.

33. *¿Qué 3 tipos de formatos de datos hemos visto? ¿Que similitudes y diferencias tienen?*
Hay tres tipos de formatos de datos: El primero es *SV, o valores separados por cualquier valor. Los más comunes son los valores separados por comas o CSV que se visualizan como una tabla simple de filas y columnas. Los CSV son los formatos de datos más sencillos pero muy utilizados en los catálogos de Datos abiertos.
El segundo formato es el JSOn o JavaScript Object Notation, que son los ficheros por excelencia de las aplicaciones web porque son los que mejor funcionan con el formato. Son más complejos que los *SV, lo que también provoca que sean más complicados de leer.
El último tipo de formato es el XML o extensible Markup Language, los más complicados de leer y los que mayor dificultad tienen a la hora de trabajar con ellos.Da la posibilidad de definir lenguajes de marcado adecuados a cada aplicación donde queramos usarlo. 

39. *¿Qué se puede hacer para ver el contenido de un archivo de texto?*
Se pueden utilizar dos comandos, el comando type para visualizar el contenido por pantallas o páginas, o el comando nano para visualizarlo con líneas, que nos permitirá también editar el texto.

42. *¿En qué se diferencian las rutas absolutas de las relativas? Pon ejemplos de ambas.*
Las rutas absolutas indican toda la ruta del archivo incluyendo el directorio raíz. Es una lista de nombres de directorios, carpetas y archivos separados por barras. Siempre comienza con la letra de unidad (como C:.) Representa la ruta completa del recurso, desde este directorio raíz hasta el archivo concreto. La ruta relativa, por su parte, representa solo una parte de esta ruta, porque se parte del directorio actual desde el que se trabaja. En vez de partir del directorio raíz, parte desde la carpeta o el directorio en el que nos encontramos. 

Por poner un ejemplo, si quiero buscar un documento llamado “comentario-datawrapper.html” alojado en la carpeta “docs” de mi directorio “uc3m-periodismo-datos-cris” de mi ordenador la ruta absoluta sería “/Users/cristinaschoenleinjaurena/uc3m-periodismo-datos-cris/docs/comentario-datawrapper.html” Si quisiera obtener solamente la ruta relativa del archivo estando yo alojada en mi repositorio “uc3m-periodismo-datos-cris” la ruta sería “docs/comentario-datawrapper.html”.
43. *Qué son las entidades HTML y cómo se representan. Por un ejemplo*
Una entidad HTML es un conjunto de caracteres o "string" que comienza con un ampersand (&) y termina con un punto y coma (;). Las entidades HTML también nos sirven para conocer que en todos los lenguajes informáticos existen los caracteres reservados, es decir, caracteres que no podemos usar explícitamente porque el lenguaje los entiende de una manera especial. 
Si quisiéramos poner una expresión matemática del tipo 10<12, pero en HTML el carácter < (menor que) es el inicio de una etiqueta. Por tanto, habrá que poner la entidad de ese carácter y sustituir el símbolo < por &lt (por lower than)

46. *¿Qué función tiene la almohadilla en Markdown y en un programa de la shell? Razona tu respuesta.*En los archivos de configuración de la Shell, la almohadilla que aparece al principio de línea hace referencia a un comentario, es decir, el programa no va a leer la línea, son indicaciones para el lector de la plantilla que el programa no tiene que leer. En Markdown el mismo carácter es el equivalente del elemento h1 de HTML o "encabezamiento de primer nivel", sirve para destacar tipográficamente el título. Mientras que los encabezados en HTML se escriben <h1>, <h2>, etc., siendo el <h1> el de mayor tamaño, en Markdown se escriben con almohadillas, siendo # el encabezado más grande, ## uno intermedio y así sucesivamente. 

47. *¿Dónde se guarda la configuración de tu shell? ¿Cuál es tu versión?*
La terminal descarga por defecto un espacio de usuario donde se van almacenando los archivos por defecto en el perfil local del usuario, para acceder a la ruta hay que ejecutar el comando echo $PATH, en mi caso, por ejemplo, se almacena en “/usr/local/bin:/usr/bin:/bin:/usr/sbin:/sbin:/Library/Apple/usr/bin,”. Mi versión de la Shell es ZSH, a la que he accedido con el comando echo $0.

48. *¿Cuál es el nombre de tu cuenta para localhost?*
Localhost es el equipo local. Un servidor virtual de nuestro ordenador en la red de redes que es Internet. Para conocer el nombre de nuestro localhost hay que introducir en nuestra terminal el comando hostname. En mi caso, mi hostname es MacBook-Pro-de-Cristina.local.

51. *¿Qué comandos o expresiones le pasarías a =lolcat=? Pon un ejemplo.*
Lolcat es una herramienta de comandos que utiliza los colores del arcoíris para colorear la información que le pidas mediante la concatenación (al igual que cat). Podría utilizarse en combinación con echo “texto deseado” | lolcat para que resulte la información que has enviado con echo de colores. Es también interesante utilizar el comando figlet “texto deseado” | lolcat, que hará que aparezca en tu terminal tu mensaje en forma de banner con los colores del arcoíris. También podría usarse sl | lolcat, y aparecerá en la terminal  un tren de colores que se desplazará por la pantalla.

52. *¿Cómo ves todos los dialectos de la shell disponibles?*
Para conocer los dialectos disponibles de la Shell debemos introducir en la terminal el siguiente comando “cat /etc/shells”. En el caso de mi Shell, los dialectos disponibles son: /bin/bash, /bin/csh, /bin/dash, /bin/ksh, /bin/sh, /bin/tcsh, /bin/zsh.

54. *Cómo realizas algún cambio en tu repositorio local y lo actualizas también en Github. Explica los pasos.*
Para realizar los cambios en mi repositorio tendría que acceder en primer lugar a la terminal y modificar el archivo que desee: podría ser un cambio de nombre o una modificación en un editor de texto como Nano. Entraríamos en la terminal y accederíamos al archivo entrando en el repositorio conectado a Github y a las carpetas donde se aloje el archivo mediante el comando cd. Una vez modificado el archivo deseado, tendríamos que llevar a cabo las siguientes acciones: ejecutar el comando git add “el-nombre-del-archivo-cambiado”, después ejecutar git commit -m “el comentario del cambio” y git push origin main para publicar estos cambios en nuestro repositorio virtual. Con estos pasos ya tendríamos actualizado nuestro archivo. 

55. *Explica los pasos para clonar en tu ordenador un repositorio de Github.*
Una vez introducido en la carpeta en la que queramos clonar el documento mediante el comando cd, debermos utilizar el comando git clone “URL-repositorio-para-clonar”. Así se creará una carpeta que será el repositorio de git en nuestro ordenador, el localhost, que tendrá la misma distribución y el mismo contenido que la dirección desde donde se ha clonado. En caso de que queramos actualizar más adelante ese repositorio nuevo que hemos creado debermos utilizar el comando git pull para actualizar nuestro repositorio local de los cambios realizados en el repositorio de Github.

62. *Explica la diferencia entre filas y columnas*
Una fila es una serie de datos colocados de forma horizontal mientras que la columna refiere a unos datos colocados verticalmente en una hoja de cálculo o una tabla. Cabe destacar que los valores separados por comas o CSV se visualizan mediante este sistema de una tabla simple de filas y columnas puesto que.las columnas se separan por comas y las filas por saltos de línea.

64. *Qué es una Faceta de texto*
Las facetas son formas de filtración de datos que se utilizan en OpenRefine para tratar en bloque los diferentes grupos de datos. Se pueden aplicar a cualquier tipo de dato, sea texto, número o fecha. En este caso, una faceta de Texto indica al programa que debe estudiar los datos de texto. Esta clasificación permite contar los registros asociados a cada texto y seleccionar aquellos que nos interesen para el estudio. Para crear esta faceta deberás cargar los datos en Openrefine, seleccionar las celdas o columnas que quieras utilizar con el criterio de texto y clasificarlas mediante la Faceta de texto.

65. *Qué es una faceta numérica*
La faceta numérica es una forma de clasificación de datos de Openrefine que permite tratar en bloque los datos de campos numéricos. Esto puede resultar interesante para detectar valores fuera de los rangos que interesen para el análisis o la investigación, o seleccionar los valores máximos o mínimos puesto que se creará una línea numérica que representa las tendencias de los datos. Para crear esta faceta deberás cargar los datos en Openrefine, seleccionar las celdas o columnas que quieras utilizar con el criterio de número y clasificarlas mediante la Faceta numérica.

66. *Qué es una faceta temporal*
En el caso de la faceta temporal, Openrefine te da la opción de agrupar todos los datos que el programa reconoce como fechas. De esta manera, creará una línea de tiempo y en ella podrás escoger los datos que te interesen para tu análisis y descartar los que no quieras utilizar mediante la clasiciación. Para crear esta faceta deberás cargar los datos en Openrefine, seleccionar las celdas o columnas que quieras estudiar con el criterio de fecha y transformarlas mediante la Timeline Facet.

68. *Como convertirías markdown a html desde pandoc*
Una vez instalado Pandoc desde la terminal con los comandos “apt-cyg install pandoc” en Windows o “brew install pandoc” en Mac. Para convertir un archivo en lenguaje markdown a html deberás abrir tu terminal, localizar el archivo markdown e y conocer su ruta. Ejecutaremos el comando pandoc “ruta-archivo/nombre-archivo.md” y nos aparecerá en pantalla como resultado la conversión del archivo en formato html que deberemos copiar.

71. *Para qué usas cd y cómo.*
El comando cd tiene unas funciones elementales: para empezar, sirve para cambiar e introducirte en un directorio concreto utilizando el comando cd “ruta-directorio”, o para salir de una carpeta o directorio concreto utilizando el comando solo, cd para salir al directorio principal.

72. *Para qué usas cp y cómo.*
El comando cp se utiliza para copiar un archivo concreto o carpeta desde la terminal. Se utilizaría directamente cp “ruta/nombre-archivo” o directamente la ruta relativa “nombre-archivo” si estás alojado en la carpeta contenedora. Es muy útil para copiar archivos que después tienes que pegar en otra carpeta e incluso duplicarlo.

73. *Para qué usas mv y cómo.*
El comando mv tiene dos funciones fundamentales: cambiar el nombre de un archivo o directorio y también moverlo a otra carpeta. Para mover archivos habría que ejecutar mv “nombre-archivo” “/ruta-destino”. En cambio, para modificarle el nombre al archivo tendrá que utilizarse el comando mv “nombre-actual” “nombre-deseado”.

74. *Para qué usas mkdir y cómo*
El comando mkdir se utiliza fundamentalmente con el objetivo de crear un nuevo directorio o carpeta de archivos. Significa make subdirectory. También permite crear varios directorios de forma simultánea. Para crear un nuevo directorio, deberá ejecutarse mkdir “nombre-nuevo-directorio”. Para crear varios directorios deberá hacerse de la siguiente manera: mkdir [directorio-nuevo-1] [directorio-nuevo-2] y así consecutivamente en todos los directorios que queramos crear.

79. *¿Qué es una API. Pon algún ejemplo.*
Una API o interfaz de programación de aplicaciones es un conjunto de definiciones y protocolos que se usa para diseñar e integrar el software de las aplicaciones. En definitiva, los códigos para comunicarse con una web. Un ejemplo es HTTP (HTTPS: la S es de sitio seguro) 
80. *¿Qué es Markdown?*
Markdown es una sintaxis simple y un parseador o conversor de su sintaxis en HTML. Fue creado por Dan Gruber al observar que el lenguaje web html era difícil de leer. El objetivo de este lenguaje es crear texto en markdown que pueda presentarse en formato html pero que sea simple de leer. Por ejemplo, si usaramos markdown en un archivo subido en Github, la plataforma lo mostraría como HTML, pero el código fuente estaría en lenguaje Markdown. Aún así, Markdown permite usar lenguaje HTML en caso de que no exista la opción de HTML.

83. *Apunta tres comandos que hayas utilizado y para qué.*
Los tres comandos fundamentales que he utilizado en mi terminal han sido:
El primero, el comando “ls”. Este comando sirve para listar los contenidos que tiene una carpeta o directorio. Me ha resultado muy útil para localizar archivos y para conocer con qué nombre lo había guardado exactamente. 
El segundo comando que he utilizado mucho ha sido pwd, que indica en qué directorio o carpeta te encuentras en este momento. Es interesante también utilizarlo para conocer la ruta de un archivo concreto.
El tercer comando que he utilizado ha sido rmdir, para eliminar directorios. Lo he utilizado para eliminar carpetas que ya no necesitaba o no quería que apareciera en mi repositorio. 

93. *¿Cómo harías para que OpenRefine interpretara correctamente los tipos de datos?*
Para que OpenRefine interprete correctamente los datos, primero hay que subirlos a la plataforma en un formato adecuado, como podría ser CSV. Una vez subidos, lo interesante sería clasificar cada uno de los datos en función de sus características. Para ello, tendríamos que Editar las columnas mediante “Edit Cells” y transformarlas al formato que deseemos, sea un número, una fecha, texto… mediante la opción “Common Transforms”. Esta opción no solo nos permite clasificar los datos, sino que el programa los interprete de forma adecuada y que podamos trabajar con ellos en función del tipo de dato. Por ejemplo, esta opción permitirá realizar una faceta de línea temporal para visualizar la evolución en el tiempo de un dato en concreto, solamente por elegir el formato fecha.

98. *Cuál es la diferencia entre XLS y XLSX. Explica la respuesta*
Tanto XLS como XLSX	 es la extensión que idetnifica los archivos de Microsoft Excel. La diferencia fundamental está en que los archivos con la extensión XLS son los creados con las versiones del programa del 97 al 2003. A partir de este año, se comenzaron a crear archivos con la extensión XLSX. Los archivos XLS son más rápidos, legibles por todas las versiones de Microsoft Excel, el formato binario, mientras que los archivos XLSX son más lentos, sobre todo en los archivos que requieren de una fórmula compleja, solo legibles por versiones de 2007 y posteriores, en formato XML abierto. Aún así, la diferencia fundamental es la de las versiones. A pesar de este cambio a partir de 2007, Excel permite guardar tus archivos con la extensión más antigua XLS para que sea compatible con todas las versiones del programa.

100. *¿Quién es Philip Meyer?* Philip Meyer fue un periodista estadounidense que comenzó su trabajo en el Miami Herald donde denunció el alto coste de los seguros escolares contra incendios y huracanes. Es considerado hoy ne día como el precursor del periodismo de datos por su forma de trabajo y ser autor del libro periodismo de precisión, considerado el precursor del periodismo de datos.
Percibió que, en esa época, en las ciencias electorales se estaban empleando herramientas informáticas, pero en el periodismo no. 
Se dio a conocer en el campo del periodismo de datos con su trabajo sobre las Detroit Riots en el verano de 1967 en las que, tras una semana de incidentes, murieron 46 personas. Además de las historias periodísticas claras, se propuso realizar una encuesta que buscase las causas de la revuelta. En Watts, en 1965, hubo otra revuelta sobre la que se realizó un informe que llevó dos años de elaboración por la Universidad de California. Con la metodología que se había empleado en esa situación, intentó reproducir el estudio en Detroit pero para que le llevase dos/tres semanas hacerlo, puesto que le acuciaba la actualidad periodística. 

101. *¿Quién fue Florence Nightingale?*
Fue una Enfermera, escritora y estadística. Considerada pionera de la enfermería moderna por ser la creadora del primer modelo conceptual de enfermería. Al ser destinada en la Guerra de Crimea, creó visualizaciones de datos de los fallecidos en el conflicto. 

