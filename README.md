¿Qué es Webpack?
básicamente webpack es un paquete de módulos y esto lo que hace es que nuestra aplicación
puede tener archivos JavaScript o jsx, archivos sass, imágenes y empaquetarlos
como si fuera una caja (todo en uno)

Webpack se puede configurar desde la terminal usando un CLI o un archivo de
configuración especial llamado webpack.config.js

Conceptos Básicos Webpack
.
Entry (punto de entrada): este le indica a webpack cual modulo de JavaScript debe de usar
para empezar a crear una salida.
Ejemplo : index.js. también podemos tener múltiples puntos de entrada pero eso es otra historia.

Output (punto de salida): Este archivo es el bundle o nuestro archivo de salida,
seria nuestra caja donde empaquetamos toda nuestra aplicación, normalmente este archivo
final se crea en una carpeta llamada dist

Loader (transformador): Los loaders lo que hacen es decirle a webpack como tiene que transformar el código de un modulo en concreto. Ejemplo : Los loaders pueden transformar ficheros a JavaScript, o cargar CSS directamente en archivos JS, (si usas reactjs ya sabrás como)

Plugins (complementos): Nos van a ayudar a extender las funcionalidades con los loaders,
añadir otras configuraciones.
Ejemplo : hay un modulo llamado HTMLWebpackPlugin que este se encarga de crear un HTML
personalizado que le inyecta todos los bundles finales que compilamos.

¿Qué es Babel?
Es un transcompilador de JavaScript que agarra el código ECMAScript 2015 en adelante y lo transforma en una versión que todos los navegadores anteriores lo puedan usar

HtmlWebpackPlugin
Es un plugin para inyectar javascript, css, favicons, y nos facilita la tarea de enlazar los bundles a nuestro template HTML.

Loaders para CSS y preprocesadores de CSS

Un preprocesador CSS es un programa que te permite generar CSS a partir de la syntax única del preprocesador. Existen varios preprocesadores CSS de los cuales escoger, sin embargo, la mayoría de preprocesadores CSS añadirán algunas características que no existen en CSS puro, como variable, mixins, selectores anidados, entre otros. Estas características hacen la estructura de CSS más legible y fácil de mantener.

post procesadores son herramientas que procesan el CSS y lo transforman en una nueva hoja de CSS que le permiten optimizar y automatizar los estilos para los navegadores actuales
