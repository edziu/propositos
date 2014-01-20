# Dart: Primeros pasos

Dart es una plataforma, un conjunto de herramientas y un ecosistema alrededor de la creación de aplicaciones web; fue creado por Google en el 2011 pero apenas llegó a su versión estable el 14 de Noviembre del 2013.

Es importante saber qué nos incluye Dart:

* **Un lenguaje de programación:** El cual es llamado Dartlang.
* **Unas librerías:** Nos incluye unas librerías para comenzar a trabajar, unas de estas son: *dart:io*, *dart:html*, *dart:json*, *dart:async*, *etc*.
* **Una máquina virtual:** Para interpretar el código de Dart.
* **Un administrador de paquetes:** Es llamado *Pub*, se encarga de manejar las dependencias de nuestro proyecto. Es similar a NPM de Node.JS.

Dartlang es un lenguaje open-source y su principal objetivo es ser una alternativa a Javascript, es por eso que desde su creación se enfocó en arreglar los problemas que Javascript tiene.

Dartlang es un lenguaje puramente orientado a objetos y basado en clases. Dartlang también cuenta con tipado estático opcional, lo cual significa que si el desarrollador lo desea, puede agregarle tipos a las variables.

Dartlang puede ser compilado a Javascript, gracias a la herramientas Dart2JS, para así lograr que nuestro código funcione en los navegadores que no incluyan la máquina virtual de Dart. Se ha hecho mucho incapié en el gran rendimiento que tiene el código resultado de esta herramienta, ya que es más rápido que el equivalente idiomático en Javascript.

## Cómo instalar nuestro entorno de desarrollo

Ya tenemos una idea básica de que es Dart. Ahora lo que sigue es comenzar a utilizarlo, para esto tenemos 2 formas:

1. Descargar el Dart Editor que es un IDE basado en Eclipse y nos incluye el SDK de Dart.
2. Descargar un plugin para nuestro IDE o editor de texto favorito.

En este tutorial vamos a hacerlo de la primer forma, para ahorrarnos tiempo de configuración del SDK.

Lo primero es ir a la [página oficial de Dart](https://www.dartlang.org/) y lo primero que nos encontraremos será un botón que dice **Descargar Dart** seguido de el nombre de la plataforma donde nos encontremos entre paréntesis. Obviamente haremos click allí y esperamos mientras nos descarga el Dart Editor.

Cuando nuestro IDE se haya terminado de descargar, solamente debemos descomprimir la carpeta *.zip* y hacer click en el fichero "Dart Editor". ¡Eso es todo! No hay necesidad de instalar nada.

Si se desea, se puede mover el folder al escritorio o al directorio donde se tengan las aplicaciones. En mi caso, utilizo OS X y moví el folder al directorio /Aplicaciones/.

Al abrirlo nos debería aparecer algo así:
![Dart Editor](http://imgur.com/8yPBmsu.png)

Mostrandonos a la izquierda los proyectos que hemos creado (en mi caso *To-Do List*), las librerías que incluye el Dart SDK y por último las librerías instaladas en nuestra máquina gracias a Pub.

Ya tenemos nuestro IDE funcionando. En los próximos tutoriales comenzaremos a programar en Dartlang.