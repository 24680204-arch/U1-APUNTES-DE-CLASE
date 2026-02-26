# U1-APUNTES-DE-CLASE
-------
Este repositorio contiene los apuntes de clase de la Unidad I, desarrollados a partir de una investigación documental en él se presentan los temas teóricos de la unidad organizados de manera clara para facilitar su comprensión y consulta como material de apoyo académico

------
## 📑 Índice
- [Unidad I. Introducción a la graficación por computadora](#unidad-i-introducción-a-la-graficación-por-computadora)
  - [1.1 Historia y evolución de la graficación por computadora](#11-historia-y-evolución-de-la-graficación-por-computadora)
  - [1.2 Áreas de aplicación](#12-áreas-de-aplicación)
  - [1.3 Aspectos matemáticos de la graficación](#13-aspectos-matemáticos-de-la-graficación)
  - [1.4 Modelos del color: RGB, CMY, HSV y HSL](#14-modelos-del-color-rgb-cmy-hsv-y-hsl)
  - [1.5 Representación y trazo de líneas y polígonos](#15-representación-y-trazo-de-líneas-y-polígonos)
  - [1.5.1 Formatos de imagen](#151-formatos-de-imagen)
  - [1.6 Procesamiento de mapas de bits](#16-procesamiento-de-mapas-de-bits)
  - [Bibliografía](#bibliografia)
    
------
Unidad I. Introducción a la graficación por computadora. 
----------
La graficación por computadora es una rama de la informática que se encarga de la generación, representación y manipulación de imágenes mediante sistemas computacionales. Su objetivo principal es crear representaciones visuales de información, objetos y fenómenos, ya sean reales o imaginarios, facilitando su análisis, interpretación y comunicación.

Esta disciplina combina conocimientos de matemáticas, programación, física, ingeniería y diseño, y es fundamental en el desarrollo de tecnologías modernas como los videojuegos, el cine digital, la simulación y el diseño asistido por computadora

-------
1.1. Historia y evolución de la graficación por computadora.
-----
Los gráficos por computadora son una herramienta esencial en la actualidad, ya que permiten la creación de imágenes y animaciones digitales de alta calidad utilizadas en diversas industrias como la publicidad, el cine, los videojuegos, la arquitectura y la ingeniería, entre otras. Sin embargo, los orígenes de los gráficos por computadora se remontan a mediados del siglo XX, cuando los primeros ordenadores comenzaron a ser utilizados para procesos de cálculo y análisis de datos.

En 1950, el matemático Maurice Wilkes desarrolló el primer sistema gráfico por computadora en el Laboratorio de Matemáticas de la Universidad de Cambridge, Reino Unido. Este sistema permitía la visualización de gráficos y datos en una pantalla de tubo de rayos catódicos (CRT) y fue utilizado principalmente para la investigación científica.

En la década de 1960, la empresa IBM desarrolló el primer sistema de gráficos por computadora comercial, conocido como el IBM 2250 Graphics Display Unit. Este sistema permitía la creación de gráficos vectoriales y fue utilizado principalmente en aplicaciones de diseño e ingeniería.

En 1963, Ivan Sutherland, un pionero en el campo de los gráficos por computadora, desarrolló el primer sistema de dibujo por ordenador, conocido como Sketchpad. Este sistema permitía la creación de dibujos en una pantalla CRT utilizando un lápiz óptico y fue utilizado principalmente en investigaciones académicas.

En la década de 1970, se produjo un gran avance en la tecnología de los gráficos por computadora con la introducción de los graficadores o plotters, dispositivos que permitían la creación de gráficos vectoriales precisos utilizando un lápiz o pluma para trazar sobre papel. Estos dispositivos fueron utilizados principalmente en aplicaciones de diseño e ingeniería.

En la década de 1980, los gráficos por computadora comenzaron a utilizarse en la industria del cine y la televisión, gracias a la introducción de software especializado como Autodesk y Softimage. Estos programas permitían la creación de animaciones y efectos especiales en 3D.

En la actualidad, los gráficos por computadora siguen evolucionando y mejorando, con la introducción de nuevas tecnologías como la realidad virtual y aumentada. Los avances en esta área han permitido la creación de experiencias visuales cada vez más realistas e inmersivas.


<img width="582" height="320" alt="image" src="https://github.com/user-attachments/assets/f942e241-021e-418a-a049-4abfc9980f38" />

----------------------------------
1.2. Áreas de aplicación.
-------
Las áreas donde se aplica la graficación por computadora son diversas y abarcan campos como la arquitectura, diseño industrial, CAD/CAM, desarrollo de aplicaciones web, laboratorios virtuales, robótica, entrenamiento virtual, simulaciones, aplicaciones forenses, recreación de situaciones especiales, rehabilitación, sistemas geográficos, meteorología, visualización científica, ingeniería en todas sus disciplinas, medicina, desarrollo de interfaces humano-computadora, reconstrucción de sitios arqueológicos, arte, educación, entretenimiento (videojuegos, películas, televisión, publicidad), y muchos otros.

--------
1.3. Aspectos matemáticos de la graficación.
--------

La graficación por computadora se fundamenta en distintas ramas de las matemáticas. Entre las más importantes se encuentran el álgebra, la geometría y el análisis matemático, las cuales permiten representar y manipular objetos gráficos de forma precisa. El álgebra se utiliza para trabajar con ecuaciones, funciones, vectores y matrices, elementos esenciales en la representación de gráficos.

Por otra parte, la geometría aporta los sistemas de coordenadas y las transformaciones geométricas como traslación, rotación y escalado. Estos conceptos permiten modelar objetos en dos y tres dimensiones y lograr representaciones realistas dentro de los sistemas de graficación por computadora.


## 1.4 Modelos del color: RGB, CMY, HSV y HSL

¿Qué es un modelo de color?

Un modelo de color establece un conjunto de colores primarios a partir de los que, mediante mezclas, se pueden obtener otros colores hasta cubrir todo el espectro visible, además del propio blanco, negro y grises, y aún más. Por ejemplo, hay colores, como el marrón o el magenta, que no están presentes en el espectro visible, y es nuestro cerebro el que lo interpreta a partir de la combinación de ondas con diferentes longitudes.

<img width="217" height="206" alt="image" src="https://github.com/user-attachments/assets/527d05dc-ce8d-4172-9cde-d74f23545578" />

RGB: 
El modelo RBG se utiliza cuando se representa color mediante haces de luz (pantallas o monitores). Un pixel en un monitor se representaría mediante tres subpíxeles o células: una roja, una verde y una azul, correspondiendo cada una a un LED o diodo emisor de luz del respectivo color. Si los tres diodos están apagados, obtendríamos el negro. Si están encendidos a diferentes intensidades, obtendríamos colores, si están todos encendidos con la misma intensidad y al máximo, tendríamos el blanco, y si la intensidad es menor pero igual en los tres diodos, obtendríamos grises.

<img width="198" height="198" alt="image" src="https://github.com/user-attachments/assets/6fc0d489-ca71-419a-bd9c-23df2559cceb" />

CMYK: 

Es un modelo sustractivo y se utiliza en impresión a partir de pigmentos de tres colores básicos: C – cian, M – magenta y Y – amarillo. La K viene del negro, ya que la combinación de los tres anteriores produce un negro poco puro, de ahí que se añada al modelo un pigmento negro puro. Al contrario que en RGB, donde el negro es la ausencia de luz, en CMYK el blanco se representa aquí como ausencia de pigmentos.

Los colores intermedios se producen a partir de la mezcla en distintas proporciones de los pigmentos base.

Hay una relación entre los modelos RGB y CMYK, ya que con la mezcla a igual parte de cada uno de los colores básicos de un modelo obtenemos los primarios del otro.

En RGB (rojo, verde, azul):

  -Rojo y verde en iguales proporciones: obtenemos amarillo – Y de CMYK
  -Rojo y azul en iguales proporciones: obtenemos el magenta – M
  -Verde y azul en iguales proporciones: obtenemos el cian – C

 En CMYK (cian, magenta, amarillo):
-Cian y magenta en igual proporción: obtenemos el azul
-Cian y amarillo en igual proporción: obtenemos el verde
-Magenta y amarillo en igual proporción: obtenemos el rojo

<img width="271" height="173" alt="image" src="https://github.com/user-attachments/assets/442bab0d-0e53-4c59-bbdb-eed76e90b647" />


Estos modelos incluyen otros dos parámetros adicionales al matiz o croma para obtener el color, que son la saturación (en ambos) y el valor (en HSV) o la luminosidad o tono (en HSL). De ahí sus siglas: HSL (H – hue o matiz, S – saturation o saturación, L – luminosity o luminosidad/tono), HSV (idem excepto V de value o valor). La diferencia entre HSV y HSL es que en HSV la saturación va del color puro al blanco, y en HSL la saturación va del color puro al gris medio, y el tono, en HSV va desde el negro al color, y en HSL va desde el negro al blanco. De ahí que HSL sea el que se utiliza más comúnmente en fotografía.
Lightroom, que se basa en HSL, dispone de controles para alterar H – matiz, S – saturación y L – Tono para los siguientes colores: rojo, naranja, amarillo, verde, cian, azul, violeta y magenta. Siguiendo con Lightroom, éste nos permite fijar la saturación entre gris y color puro para esos 8 colores. Respecto al matiz, nos permite virar los 8 colores a los adyacentes que comentaba en el artículo de luz y color, por ejemplo, para el rojo, desde magenta a naranja. Por último, respecto al tono, Lightroom nos permite oscurecer cada uno de esos 8 colores hasta el negro, o bien aclararlo hasta llegar al blanco.


<img width="293" height="124" alt="image" src="https://github.com/user-attachments/assets/6c45d10e-1d06-49f0-a84b-a1ce7347801a" />

--------
1.5. Representación y trazo de líneas y polígonos.
-----
La representación y trazo de líneas y polígonos es un tema fundamental en la graficación por computadora, ya que sienta las bases para dibujar cualquier objeto en la pantalla. Las pantallas de las computadoras están formadas por una cuadrícula de píxeles, y para dibujar una figura, necesitamos algoritmos que determinen qué píxeles deben encenderse

----
1.5.1 Formatos de imagen.
-------
Poligono
<img width="1365" height="715" alt="image" src="https://github.com/user-attachments/assets/1a2d2e02-db00-4e73-86d3-a7c5d124abb7" />

En este código se utiliza Python dentro de Blender para crear un polígono de forma automática. Primero se cargan las herramientas necesarias para poder trabajar en Blender y hacer los cálculos matemáticos. Después se crea una función donde se indica el nombre del objeto, cuántos lados tendrá el polígono y qué tan grande será mediante el radio. El programa calcula la posición de cada punto del polígono usando fórmulas matemáticas y los distribuye de manera uniforme formando un círculo, manteniendo la figura en dos dimensiones. Una vez obtenidos los puntos, estos se conectan para formar las aristas del polígono y se muestra el objeto en la escena. Al final, el código se ejecuta para generar un hexágono, demostrando cómo se puede crear geometría de forma automática sin necesidad de dibujarla manualmente

------
Flor de vida
<img width="1365" height="716" alt="image" src="https://github.com/user-attachments/assets/55e3e5ab-72e6-4b02-8b9a-b9dc9473b466" />

En este código se utiliza Python dentro de Blender para crear de manera automática una figura conocida como la “Flor de la Vida”. Primero se limpia la escena para evitar que queden objetos anteriores y se definen los valores principales, como el radio de los círculos y el ángulo de separación entre ellos. El programa comienza creando un círculo central y, a partir de ahí, usa un ciclo while para generar círculos alrededor, calculando su posición con funciones matemáticas que convierten ángulos en coordenadas. De esta forma, cada círculo se coloca de manera uniforme alrededor del centro, formando el patrón característico. Todo el proceso se realiza de forma automática, lo que permite generar la figura completa sin necesidad de dibujar cada círculo manualmente en Blender

------
1.6. Procesamiento de mapas de bits.  
-----
Los mapas de bits, también conocidos como imágenes raster, son representaciones digitales de imágenes que consisten en una cuadrícula de píxeles (elementos de imagen rectangulares). Cada píxel tiene un valor que determina su color y posición en la imagen. La calidad de una imagen raster se define por su resolución y profundidad de color.

Importancia del Procesamiento de Mapas de Bits en Diseño Gráfico y Edición de Imágenes:

El procesamiento de mapas de bits es esencial en diseño gráfico y edición de imágenes, ya que permite la manipulación y mejora de fotografías y gráficos. Esto incluye ajustar el aspecto visual, eliminar imperfecciones, aplicar efectos especiales y componer imágenes. El procesamiento de mapas de bits es fundamental para crear contenido visual atractivo y profesional.

Estructura de un Mapa de Bits: Píxeles y Resolución:

* Píxeles: Los píxeles son los elementos de imagen individuales en un mapa de bits. Cada píxel tiene un valor de color y se coloca en una ubicación específica en la cuadrícula.

* Resolución: La resolución de un mapa de bits se refiere al número de píxeles en la imagen. Una mayor resolución implica más detalles, pero también un archivo más grande.

<a id="bibliografia"></a>
## Bibliografía

-Hearn, D., & Baker, M. P. (2011). Computer graphics with OpenGL (4th ed.). Pearson Education.

-Shirley, P., Marschner, S., & Ramamoorthi, R. (2009). Fundamentals of computer graphics (3rd ed.). A K Peters.

-Gonzalez, R. C., & Woods, R. E. (2018). Digital image processing (4th ed.). Pearson.

-Foley, J. D., van Dam, A., Feiner, S. K., & Hughes, J. F. (2014). Computer graphics: Principles and practice (3rd ed.). Pearson Education.

-Angel, E., & Shreiner, D. (2018). Interactive computer graphics: A top-down approach with WebGL (7th ed.). Pearson.
