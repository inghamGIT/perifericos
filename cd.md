# Historia

El disco compacto (conocido popularmente como CD por siglas en inglés de Compact Disc) es un disco óptico utilizado para almacenar datos en formato digital, consistentes en cualquier tipo de información.

El disco compacto es una evolución tecnológica del Laserdisc. Los prototipos fueron desarrollados por Philips y Sony, primero de manera independiente y posteriormente de manera conjunta. Fue presentado en junio de 1980 a la industria, y se adhirieron al nuevo producto 40 compañías de todo el mundo mediante la obtención de las licencias correspondientes para la producción de reproductores y discos.

Originalmente salió al mercado como un contenedor de audio, pero en 1984 empezaron a aparecer modelos orientados a almacenar datos.

Para poner la memoria del disco compacto en contexto, una novela promedio contiene 60 000 palabras. Si se asume que una
palabra promedio tiene diez letras y cada letra ocupa un byte, una novela por lo tanto ocuparía 600 000 bytes (600 Kb). Un CD puede por lo tanto contener más de 1000 novelas. Si cada novela ocupa por lo menos un centímetro en un estante, entonces un CD puede contener el equivalente de más de diez metros en el estante. Sin embargo, los datos textuales pueden ser comprimidos diez veces más, usando algoritmos compresores; por lo tanto, un CD-ROM puede almacenar el equivalente a más de 100 metros de estante.

El éxito del disco compacto fue casi inmediato, especialmente en el ámbito de la industria musical, en el que rápidamente reemplazó a las cintas magnéticas. A principios de los años 90 empezaron a salir los primeros grabadores de CD para particulares, catapultando su popularidad en el sector informático.

El CD continuó como sistema de almacenamiento de referencia hasta la década de los 2000, donde fue paulatinamente reemplazado por su sucesor, el DVD.

Actualmente como soporte de datos se encuentra en desuso, pero continúa siendo el principal formato físico utilizado por la industria musical.

# Características.

Un disco compacto cuenta con un diámetro de 120mm (existe una versión mini de 80mm), con 15mm de orificio central y un grosor de 1,2mm. En su fabricación se utiliza comúnmente aluminio como material de codificación, y policarbonato como aislante.

<img src=CD.png>

El reverso de un disco óptico generalmente tiene impresa una etiqueta, hecha usualmente de papel pero a veces impresa o estampada en el disco mismo. Este lado, sin codificar, del disco es típicamente cubierto con un material transparente, en general laca. A diferencia de los disquetes, la mayoría de los discos ópticos no tienen integrada una carcasa protectora y por lo tanto son susceptibles a los problemas de transferencia de datos debido a rayaduras, grietas, huellas, y otros problemas del entorno. Aunque las huellas, el polvo y la suciedad en muchos casos pueden ser removidas con un paño húmedo.

A diferencia de otros formatos, como los disquetes, el disco compacto no requiere de una caja de plástico para proteger el contenido.

Las reacciones químicas entre sus componentes, además del calor y el maltrato, pueden destruir los datos digitales. Por lo tanto, hay que revisar periódicamente la información para detectar las fallas. Para prevenir el deterioro temprano de los compactos, solamente hay que tratarlos bien. Los CD-R, basados en tinturas orgánicas, son más perecederos y volátiles que los compactos y los CD-ROM. Hay que verificar la copia de seguridad cada 2 años o menos. Es conveniente, la práctica de hacer doble copia de todos los datos y respaldar la información cada dos años.

# Lectura y escritura.

Los discos ópticos presentan una capa interna protegida, donde se guardan los bits mediante distintas tecnologías, siendo que en todas ellas dichos bits se leen merced a un rayo láser incidente. Este, al ser reflejado, permite detectar variaciones microscópicas de propiedades óptico-reflectivas ocurridas como consecuencia de la grabación realizada en la escritura. Un sistema óptico con lentes encamina el haz luminoso, y lo enfoca como un punto en la capa del disco que almacena los datos.

Para su manipulación se requiere una unidad lectora, que proyecta un haz láser y un fotorreceptor, que recibe el haz tras rebotar en el disco. El láser suele ser un diodo AlGaAs con una longitud de onda en el aire de 780 nm por lo que resulta una luz invisible al ojo humano, pero no por ello inocua.

<img src=lectoraCD.png>

Pasos que sigue el cabezal para la lectura de un CD:

1. Un haz de luz coherente (láser) es emitido por un diodo de infrarrojos hacia un espejo que forma parte del cabezal de lectura, el cual se mueve linealmente a lo largo de la superficie del disco.
2. La luz atraviesa un divisor de haz que triplica el haz de entrada.
3. Los tres haces se enfocan sobre la superficie del CD a través de un sistema óptico; el haz central se mantiene sobre la pista, los otros dos quedan a ambos lados y son usados para el sistema de seguimiento automático de la pista (autotracking).
4. Esta luz incidente se refleja en la capa de aluminio, atravesando el recubrimiento de policarbonato. La altura de los pozos (pits) es igual en todos y está seleccionada con mucho cuidado, para que sea 1/4 de la longitud de onda del láser en el policarbonato. La idea aquí es que la luz que se refleja en un pozo viaje 1/4 + 1/4 = 1/2 de la longitud de onda más que la luz que se refleja en un llano (land).
5. La luz reflejada se encamina mediante una serie de lentes y espejos a cuatro fotodetectores montados en cuadro.
6. Cuando se produce una transición pozo-llano o llano-pozo, como hay un desfase de media longitud de onda entre ambos, se produce una interferencia destructiva y la intensidad resultante es prácticamente nula. A lo largo de un pozo, o a lo largo de un llano, no hay cambios y la intensidad resultante es máxima. Los fotodetectores sensan este cambio en la intensidad luminosa, convirtiéndolo en energía eléctrica.
7. Para recuperar la señal, se suma la salida de los cuatro fotodetectores. Se asigna un 1 a las transiciones pozo-llano o llano-pozo (intensidad mínima) y un 0 al interior de un pozo o un llano (intensidad máxima).
8. El flujo de bits así leído se decodifica en el orden inverso en que fue codificado: primero pasa por un decodificador EFM, luego por dos niveles de detección de errores (Reed-Solomon), y por último por una etapa de corrección de errores.
9. El autotracking se retroalimenta con la diferencia entre la intensidad detectada por cada sensor, para mantener el láser enfocado sobre la pista.

Se puede grabar un CD por moldeado durante la fabricación mediante un molde de níquel (CD-ROM). La fabricación de estos discos requiere disponer de una sala libre de partículas de polvo, en la cual se llevan a cabo los siguientes procesos: sobre un disco finamente pulido en grado óptico se aplica una capa de material fotosensible de alta resolución, del tipo utilizado en la fabricación de microchips. Sobre dicha capa es posible grabar la información gracias a un rayo láser. Una vez acabada la transcripción de la totalidad de la información al disco, los datos que contiene se encuentran en estado latente. El proceso es muy parecido al del revelado de una fotografía.

Dependiendo de las zonas a las que ha accedido el láser, la capa de material fotosensible se endurece o se hace soluble al aplicarle ciertos baños. Una vez concluidos los diferentes baños se dispone de una primera copia del disco que permitirá estampar las demás. Sin embargo, la película que contiene la información y está adherida a la placa de vidrio es blanda y frágil, por lo cual se hace imprescindible protegerla mediante un fino revestimiento metálico, que le confiere a la vez dureza y protección.

Finalmente, gracias a una combinación de procesos ópticos y electroquímicos, es posible depositar una capa de níquel que penetra en los huecos y se adhiere a la película metálica aplicada en primer lugar sobre la capa de vidrio. Se obtiene de este modo un disco matriz o "máster", que permite estampar a posterior miles de copias del CD-ROM en plástico.

Una vez obtenidas dichas copias, es posible serigrafiar sobre la capa de laca filtrante ultravioleta de los discos imágenes e informaciones, en uno o varios colores, que permitan identificarlo. Todo ello, lógicamente, por el lado que no contiene la información.

Otro modo de grabación es por la acción de un haz láser (CD-R y CD-RW). Para esto la grabadora crea unos pits y unos lands cambiando la reflectividad de la superficie del CD. Los pits son zonas donde el láser quema la superficie con mayor potencia, creando ahí una zona de baja reflectividad. Los lands, son justamente lo contrario, son zonas que mantienen su alta reflectividad inicial, justamente porque la potencia del láser se reduce. Según el lector detecte una secuencia de pits o lands, tendremos unos datos u otros. Para formar un pit es necesario quemar la superficie a unos 250º C. En ese momento, el policarbonato que tiene la superficie se expande hasta cubrir el espacio que quede libre, siendo suficientes entre 4 y 11 mW para quemar esta superficie, claro que el área quemada en cada pit es pequeñísima. Esto es posible ya que es una superficie algo "especial". En los discos grabables es un tinte orgánico. Para simular un pit, el grabador usa un rayo láser más potente de lo normal para dejar marcas en el tinte orgánico para que absorban la luz láser en el lector y sean interpretados como ceros. En los discos regrabables está formada en esencia por plata, telurio, indio y antimonio.
Inicialmente el disco está completamente vacío de datos. Esta superficie tiene una estructura policristalina o de alta reflectividad. Si el software le indica a la grabadora que debe simular un pit, entonces lo que hará será aumentar con el láser la temperatura de la superficie hasta los 600 o 700 °C, con lo que la superficie pasa a tener ahora una estructura no cristalina o de baja reflectividad. Cuando debe aparecer un land, entonces se baja la potencia del láser para dejar intacta la estructura policristalina. Para borrar el disco se quema la superficie a unos 200 °C durante un tiempo prolongado (de 20 a 40 minutos) haciendo retornar a su estado cristalino inicial.

# Tipos de Discos Compactos:

## CD-A

EL primer formato de disco compacto comercializado, especializado en sonido. El audio se registra en formato digital, codificado mediante el sistema PCM con una frecuencia de muestreo de 44100 muestras por segundo y con dos canales (sonido estereofónico) con una resolución de cuantificación digital de 16 bits por canal (lo que permite un rango dinámico de 96 dB). Puede guardar entre 74 y 90 minutos de audio, dependiendo de la versión.

## CD-ROM

Un CD-ROM estándar puede albergar 650 o 700 MB de datos y los especiales de gran capacidad pueden llegar a los 800 y 900 MB. Fue introducido en 1984, siendo el primer formato de CD destinado al mundo de la informática.

## CD-R

Introducido en 1988, era conocido originalmente como CD-WO (compact disc write once). Este disco permite grabar datos en él (una sola vez)mediante una unidad grabadora comercial, a unas velocidades hasta 7800RPM.

## VCD

EL VCD fue introducido en 1993 como formato de almacenamiento de vídeo y audio, con la intención de desbancar al VHS en el ámbito del video doméstico. La resolución de pantalla de un VCD es de 352x240 píxeles para el formato NTSC o de 352x288 pixeles para el formato PAL, aproximadamente la cuarta parte de la resolución normal de televisión. El vídeo y el audio de un VCD codificada en formato MPEG-1; el vídeo se almacena a una tasa de 1150 kilobits por segundo, el audio a 224 kbit/s. En general, la calidad es comparable a la del formato VHS, aunque los efectos de la compresión pueden ser apreciables. 

## CD-RW

Introducido en 1996, permite grabar datos al igual que el CD-R,con el mismo hardware, pero con la diferencia de que sus datos pueden ser borrados y grabados más de una vez.

## MiniCD

Es un disco de 80 mm que puede almacenar hasta 21 minutos de música o 180 MB de datos. Debido a su tamaño no funciona en algunos lectores,como los de los automóviles.