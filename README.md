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
