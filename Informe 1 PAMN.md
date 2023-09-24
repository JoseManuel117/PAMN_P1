||||
| :- | :-: | -: |

**Informe de accesibilidad web**

Jose Manuel Hernández Aparicio & Sheila Cazorla Rodríguez

# 1º Introducción 


En el contexto actual, donde la digitalización y la tecnología desempeñan un papel fundamental en nuestra vida cotidiana, la accesibilidad web y de aplicaciones se erige como un principio esencial para garantizar que todas las personas, independientemente de sus capacidades y discapacidades, puedan disfrutar de una experiencia en línea inclusiva y equitativa. Las Directrices de Accesibilidad para el Contenido Web (WCAG, por sus siglas en inglés) son un conjunto de estándares internacionalmente reconocidos que establecen pautas para hacer que las páginas web y las aplicaciones sean accesibles para todos.

Lamentablemente, en algunos casos, nos encontramos con que importantes actores en el mundo digital no cumplen con los estándares de accesibilidad definidos en las WCAG. En este informe, se analizarán dos casos específicos que ejemplifican esta problemática: la página web de Aliexpress y la aplicación móvil "ULPGC". Este análisis tiene como objetivo identificar y comprender las áreas en las que estas plataformas no cumplen con las WCAG, resaltando las deficiencias que impactan negativamente en la experiencia de usuario de aquellos que dependen de tecnologías adaptativas o que tienen discapacidades, limitando su capacidad para acceder y utilizar plenamente estos servicios en línea.
#

# 2º Análisis de la web
![Interfaz de usuario gráfica, Sitio web

Descripción generada automáticamente](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.001.png)

*Ilustración 1: Vista previa de la web*

- **Perceptibilidad**: La página web en cuestión presenta un fallo de perceptibilidad importante, ya que la mayoría de sus imágenes carecen de una descripción de la misma, imposibilitando que personas con discapacidades visuales puedan percibirla correctamente, ya que el modo de lectura automático no podrá interpretarlas de ninguna forma. 

Si observamos el cache de la página y lo ponemos en modo solo texto, podemos observar que si bien sí aparecen los títulos de algunos productos (no todos), la forma en la que se presenta la información es confusa:

![Texto

Descripción generada automáticamente con confianza baja](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.002.png)

*Ilustración 2: Web en modo texto plano*

Como se puede apreciar, aparecen varios precios diferentes sin dejar claro a qué hacen referencia los mismos.

Así mismo, también hay una gran cantidad de fallos en los contrastes, ya que muchas letras informativas, como las de los descuentos, tienen un tono que puede ser confundido con el fondo. Así mismo, no cuenta con un diseño responsive, ya que, si ponemos la página en modo móvil y empezamos a empequeñecer la pantalla, podremos observar como la mayoría de sus productos quedan cortados. Como se puede observar en la siguiente imagen, pa página web no se ajusta en tamaño y posición a la disposición de la pantalla. 

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.003.png)

*Ilustración 3: Vista previa de la web en un dispositivo móvil*

- **Operable**: Un inconveniente es que la navegación vía teclado por la página resulta prácticamente imposible, si intentamos navegar por ella usando el tabulador, no se los señala de ninguna forma la opción en la que estamos. Aun asumiendo que el orden que sigue es de arriba-abajo, izquierda-derecha, resulta bastante tedioso llegar a las partes más relevantes de la misma, como pueden ser las opciones de categorías, los cuales ocupan posiciones más alejadas con respecto a otras que pueden resultar menos interesantes.

Además, no es posible pausar de ninguna forma (ni con teclado ni con ratón) ninguno de los múltiples banners que hay en movimiento.

En general, la página incumple por completo este apartado, ya que no solo es excesivamente complejo moverse por ella usando el teclado, sino que también incumple múltiples principios cuando se intenta navegar con el ratón.



- **Comprensible:** Se detectó un apartado con un error de traducción, obstaculizando a los usuarios ya que el contenido no es compresible para los usuarios que han recibido la traducción errónea.

Si el usuario pulsara en el error de traducción seria redirigido a otra web la cual no detecta el idioma del propio navegador haciendo incomprensible para el usuario el uso de esta.

![Interfaz de usuario gráfica, Texto, Aplicación, Chat o mensaje de texto

Descripción generada automáticamente](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.004.png)

*Ilustración 4: Error de traducción*

![Captura de pantalla de computadora

Descripción generada automáticamente con confianza media](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.005.png)

*Ilustración 5: Redirección resultado de pulsar en el error de traducción*

En cuanto a la navegación consistente, la página falla a la hora de ser coherente con lo seleccionado, por ejemplo, en la parte inferior de la misma, se pueden ver recomendados varios artículos que supuestamente están de oferta, si seleccionamos alguno de ellos, nos redirigirá a una página alternativa en la que ni siquiera hay artículos similares al seleccionado, pero en la cual no se encuentra el artículo previamente seleccionado. 

Es decir, en lugar de llevarnos al producto que hemos elegido, nos envía a una página con recomendaciones de productos que rara vez coinciden con el artículo que queremos.

![Interfaz de usuario gráfica, Aplicación

Descripción generada automáticamente](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.006.jpeg)

*Ilustración 6: Artículos recomendados*





Al seleccionar el walkie-talkie, por ejemplo, nos redirige a una página con los siguientes productos:

![Interfaz de usuario gráfica, Sitio web

Descripción generada automáticamente](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.007.png)

Como se puede observar, de los 12 artículos mostrados, solo 1 coincide con el walkie-talkie que hemos seleccionado, y ni siquiera es el mismo modelo que elegimos previamente.

En cuanto a la sugerencia de errores, Aliexpress carece por completo de ellos ya que no verifica ninguno de los formularios que se pueden rellenar, por ejemplo, a la hora de registrarnos, se nos solicita que introduzcamos un número de teléfono, la página no verifica en absoluto dicho número, ya que permite introducir uno de menos de 9 dígitos y sigue actuando como si todo estuviera en orden:

![Interfaz de usuario gráfica, Texto, Aplicación

Descripción generada automáticamente](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.008.png)

No obstante, para otros formularios sí verifica la información introducida, como por ejemplo a la hora de introducir los datos de la tarjeta de crédito

Al dar total libertad a los vendedores, algunos productos fallan a la hora de seguir una identificación consistente, es decir, para el producto A, las opciones de “color” representan los colores del mismo, sin embargo, para el producto B, las opciones de “color” pueden representar modelos totalmente diferentes del mismo, por ejemplo:

![Interfaz de usuario gráfica

Descripción generada automáticamente](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.009.png)

En este caso los colores representan correctamente los mismos.

![Interfaz de usuario gráfica, Texto, Aplicación, Chat o mensaje de texto

Descripción generada automáticamente](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.010.png)

En este otro, los “colores” representan modelos totalmente diferentes al mostrado en la imagen principal del producto. Se podría decir que faltaría una gama de opciones diferentes para indicar el “modelo” del mismo, en vez de uno solo que sirva tanto para el color como el modelo. 

Además, muchas veces viene mezclado en la misma gama de opciones modelos y colores diferentes de los mismos.

No hemos detectado ningún otro fallo dentro de la operabilidad.

- **Robustez:**  Haciendo una inspección no hemos detectado fallos en esta área en la página.
# 3º Análisis de la App

Hemos decidido examinar la aplicación ULPGC, su versión para IOS. 

- **Perceptibilidad**: Activando los ajustes de accesibilidad de IOS para las personas con limitaciones cognitivas nos hemos encontrado con la imposibilidad de poder hacer uso de esta, ya que el narrador no es capaz de leer el contenido de las pantallas de la aplicación.

*Ilustración 7: Vista de la app*
- ![Pantalla de celular con imagen de la pantalla de un celular

Descripción generada automáticamente con confianza media](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.011.jpeg)![](Aspose.Words.44fcf0e7-8fc1-45d7-b73c-6908b1c7f4c4.012.png)**Operable**: Para un usuario promedio la navegación por la app es sencilla y agradable, ya que tiene una clara presentación visual garantizando una buena experiencia de usuario.

A la hora de intentar pasar asistencia, el profesor puede decidir hacerlo por código QR en vez de por bluetooth, sin embargo, al intentar pasarla mediante la app, no nos deja introducir el código QR de forma instantánea, en su lugar, debemos intentar pasarla mediante bluetooth obligatoriamente y, una vez expirado el tiempo de espera, sí nos dará la opción de introducir un código o escanear el código QR 

- **Comprensible:** La información se muestra correctamente, se adapta al idioma del dispositivo sin necesidad de configuración previa. 

A la hora de iniciar sesión, si bien nos indica que el DNI debe ser sin letra, no nos proporciona ningún mensaje recordatorio en caso de ponerlo. Así mismo, tampoco verifica si intentamos iniciar sesión sin haber introducido previamente una contraseña.

Tampoco comprueba si el DNI introducido tiene menos caracteres de los que debería.

- **Robustez:** El único fallo encontrado consiste en un fallo en la versión de Android, ya que no todas las páginas de la app están pasadas al modo oscuro, por lo que va saltando entre modo oscuro y modo claro en función de donde se encuentre el usuario.







||||
| :- | :-: | -: |

