# Introducción a la programación creativa en p5.js - Programa
Programa del curso de Introducción a la programación creativa en [p5.js](https://p5js.org/es) organizado por [Escuela Coded](http://codedescuela.cl), [Productora Suricata](https://productorasuricata.com/) y [Centro La Planta](http://centrolaplanta.com/).
El taller será dictado por Guillermo Montecinos - profesor de Escuela Coded -  en Centro La Planta entre los días 12 y 28 de marzo de 2018.
## Sobre el Curso
Curso de introducción a la programación creativa que busca explorar las posibilidades de los nuevos medios digitales en contextos artísticos. Durante 6 sesiones revisaremos las nociones elementales de programación que permitan la construcción de sistemas complejos, utilizando el código como herramienta facilitadora de la expresión de la creatividad.

Analizaremos referentes de las artes visuales latinoamericanas y del diseño norteamericano a través de la reinterpretación de algunas de sus obras mediante el lenguaje de programación -inspirados por el proyecto [ReCode](http://recodeproject.com/)-. De esta manera, el código será una herramienta al servicio de la creatividad desde el cual podremos analizar una obra, para luego experimentar con los elementos obtenidos de ella.

Posteriormente, revisaremos técnicas para trabajar con texto, imagen y video en un entorno web interactivo, para finalizar el curso con el desarrollo de un proyecto personal o grupal que utilice las herramientas exploradas.
## Módulo 1 - Recode: Artes visuales y p5.js
### Clase 1: Introducción a p5.js (12 de marzo)
En esta primera clase realizaremos una introducción al curso en la que plantearemos las ideas que nos motivan a enseñar el uso de un *Software Libre* ([FLOSS](https://medium.com/processing-foundation/processing-and-floss-d35aa4607f4c)) como [p5.js](https://p5js.org/es). Luego discutiremos el contexto en que se desarrollan este tipo de herramientas de programación orientadas al arte. Posteriormente analizaremos el trabajo artístico de pintora cubana [Carmen Herrera](https://en.wikipedia.org/wiki/Carmen_Herrera), para finalmente reinterpretar en código una de sus obras a través de la cual revisaremos, aplicaremos y comprenderemos la estructura y funciones básicas de p5.js, la sintaxis elemental de JavaScript.
### Temario
- Presentación del instructor y Escuela Coded
- Presentación del Curso, objetivos y alcances
- Introducción a las Artes Mediales, por [Aarón Montoya-Moraga](http://montoyamoraga.io/)
- Introducción a p5.js
- Entorno de programación: editor web
- Referencia web de [p5.js](https://p5js.org/es/reference/)
- [Carmen Herrera](https://en.wikipedia.org/wiki/Carmen_Herrera), arte abstracto
- Recode: Green & Orange
- Tarea: reprogramar una obra de Herrera aplicando los conceptos revisados. Experimentar con variaciones e integración de otras herramientas
#### Conceptos
- Estructura de p5.js
- Sintáxis de JavaScript
- Primeras figuras: [ellipse()](https://p5js.org/es/reference/#/p5/ellipse), [rect()](https://p5js.org/es/reference/#/p5/rect) y [triangle()](https://p5js.org/es/reference/#/p5/triangle)
- Color: RGB, HSB, [colorMode()](https://p5js.org/es/reference/#/p5/colorMode)
- Funciones espaciales: [push()](https://p5js.org/es/reference/#/p5/push), [pop()](https://p5js.org/es/reference/#/p5/pop), [translate()](https://p5js.org/es/reference/#/p5/translate) y [rotate()](https://p5js.org/es/reference/#/p5/rotate)
#### Referencias
- [Sesión 2. Introducción a p5.js, Coded Escuela](http://codedescuela.cl/taller1-intro-programacion-creativa-p5js-2017-05/sesiones/sesion_2/slides/#/)
- [*The 100 years show*](https://www.netflix.com/title/80106609), documental sobre Carmen Herrera
### Clase 2: Arreglos, Bucles *For* y Condicionales *If* (14 de marzo)
En esta clase volveremos a revisar y discutir el contexto de las artes mediales, poniendo el foco esta vez en las artes interactivas en entornos web. Posteriormente revisaremos la obra concreta del artista brasileño, particularmente de su ejercicio denominado *Metaesquema* el cual utilizaremos como modelo para analizar y comprender la lógica algorítmica de sus composiciones. Finalmente llevaremos al código uno de sus ejercicios de Metaesquema, a través del cual revisaremos conceptos elementales de programación como bucles for, condicionales y arreglos de variables.
- Presentación y comentarios recode Carmen Herrera
- Arte Web y Nuevos Medios, por Aarón Montoya-Moraga
- Hélio Oiticica, arte concreto
- Recode: Metaesquema
- Presentación del Proyecto Final
#### Conceptos
- Variables
- Arreglos
- Bucles For
- Condicional if
#### Referencias
- [Sesión 3. Introducción a p5.js, Coded Escuela](http://codedescuela.cl/taller1-intro-programacion-creativa-p5js-2017-05/sesiones/sesion_3/slides/#/)
## Módulo 2 - Medios: texto, imagen y video
### Clase 3: Texto en p5.js (19 de marzo)
En esta clase revisaremos pasajes de la obra de los diseñadores Muriel Cooper y John Maeda, ambos del [MIT Media Lab](https://www.media.mit.edu/), con el objeto de esbozar una idea del rol de la tipografía en el arte y diseño algorítmicos. Posteriormente, replicaremos una obra de uno de estos exponentes, con el objeto de adentrarnos en el uso de la tipografía como un objeto de diseño en p5.js. Para ello revisaremos y aplicaremos funciones que nos facilitarán el trabajo espacial de texto.
- Presentación y comentarios recode Hélio Oiticica
- Muriel Cooper y John Maeda: tipografía y diseño
- Uso de texto y fuentes en p5.js
- Importación de texto como un arreglo de puntos
- Animación de Texto
- Recode: *Japanese Poster*, de John Maeda
#### Conceptos
- Función [preload()](https://p5js.org/es/reference/#/p5/preload)
- Métodos de objeto *font*: [textBounds()](https://p5js.org/es/reference/#/p5.Font/textBounds) y [textToPints()](https://p5js.org/es/reference/#/p5.Font/textToPoints)
#### Referencias
- [Sesión 4. Introducción a p5.js, Coded Escuela](http://codedescuela.cl/taller1-intro-programacion-creativa-p5js-2017-05/sesiones/sesion_4/slides/#/)
### Clase 4: Imagen y Video en p5.js (21 de marzo)
En esta clase exploraremos las posibilidades que nos entrega p5.js para trabajar con imágenes y video. Comenzaremos importando una imagen al navegador web, la cual manipularemos y filtraremos utilizando las funciones nativas de p5.js. Posteriormente comprenderemos la imagen como una matriz de pixeles, los cuales pueden ser importados y manipulados por separado, creando filtros más complejos sobre la imagen fija. Luego aprenderemos a importar video desde la webcam utilizando el capturador de p5.js, el que desplegaremos en el navegador web y manipularemos en tiempo real.
- Importación de imágenes a p5.js
- Aplicación de filtros en p5.js
- Importación de pixeles
- Manipulación de pixeles
- Captura de video mediante webcam
- Procesamiento de imagen en vivo
#### Conceptos
- Funciones: [loadImage()](https://p5js.org/es/reference/#/p5/loadImage), [createCapture()](https://p5js.org/es/reference/#/p5/createCapture), [loadPixels()](https://p5js.org/es/reference/#/p5/loadPixels), [updatePixels()](https://p5js.org/es/reference/#/p5/updatePixels), [get()](https://p5js.org/es/reference/#/p5/get) y [set()](https://p5js.org/es/reference/#/p5/set)
#### Referencias
## Módulo 3 - Proyecto
### Clase 5 (26 de marzo)
La penúltima clase del curso estará dedicada a que cada participante trabaje en el desarrollo de su proyecto personal/grupal. El equipo Coded cumplirá el rol de facilitar y ayudar a la programacin de cada uno de los proyectos.
### Clase 6 (28 de marzo)
La última clase del curso será dividida en tres partes: 
- Cierre de proyectos
- Presentación de proyectos: Los participantes mostrarán a sus compañeros sus proyectos, describiendo su proceso, aprendizajes y logros. Se invitará a un grupo de profesores destacados quienes darán comentarios los participantes sobre su trabajo.
- Cierre de curso
## Referencias del curso
- [Libro *Getting Started in p5.js* en Español](https://github.com/processing/p5.js-getting-started-es/blob/master/v1.0.2.pdf)
- [*The Coding Train*, tutorial de YouTube de Daniel Shiffman](https://www.youtube.com/user/shiffman)

## Sobre el Instructor
Guillermo Montecinos es educador, músico e ingeniero con base en Santiago. Su trabajo se enfoca en la construcción de experiencias sonoras inmersivas que evoquen y provoquen a la audiencia a partir de la sonoridad y visualidad. Es co-fundador de [Coded, Escuela de Artes y Oficios Electrónicos](http://codedescuela.cl) (Santiago, Chile) y graduado de la [School for Poetic Computation](http://sfpc.io) (NY).<br> 
http://guillemontecinos.cl/
