# Prueba Wordpress Cannactiva

Evaluación para el desarrollo de Wordpress, elaborada por Cannactiva.

## Objetivo

El objetivo principal de esta prueba es montar un pequeño site que conste de un CPT (Custom post type) el cual se muestre como listado de 6 elementos en la home, se muestren todos los CPT en su propio listado, con el nombre que quieras darle ( Videos, Portfolio, Productos, ... ) y ver el CPT individual.

## Especificaciones

Crea un entorno local o dónde tú prefieras, puedes usar Docker, Vagrant o lo que más te convenga.

A partir de aquí deberas instalar un Wordpress en el directorio **www** del proyecto e inicializarlo, una vez este inicializado crear un Theme Child a partir de cualquiera de los temas por defecto que trae Wordpress y empezar el desarrollo.

El tema deberá tener estilos/scripts propios y ser responsive, puedes coger cualquier web de referencia para establecer estos estilos y/o funcionalidades. Adjuntamos un enlance de una web de referencia por si puede servirte de ayuda, siente libre en crear lo que quieras:

> https://magazine.deporvillage.com/

Todos los assets, a excepción de las imágenes han de estar compilados y minimizados en el tema, utilizando pre-procesadores tanto en JS como en CSS. Si ves conveniente utilizar alguna librería externa para la generación del grid, utilízala sin problema.

## Instalación


## ¿Qué nos gustaría ver?

Nos gustaría que a parte de que el objetivo de la prueba, principalmente sea logrado, puedas desarrollarla lo mejor posible. Por eso valoraremos positivamente si decides incluir algunos de los siguientes aspectos:

- Utilización de Webpack frente a Gulp para la compilación de los assets
- Nomenclatura BEM en los estilos, no utilizar jQuery para los scripts y utilizar ES6
- Creación de funcionalidades básicas como carousel de imágenes, filtros, ... Todo ello centrándote en la funcionalidad.
- Buena estructuración de carpetas/archivos
- Que nos descubras algún framework que no conozcamos y que premie la sencillez
- Que todo el contenido de la web sea administrable, ya sea por Shortcodes o Blocks.

## Delivery

Necesitaremos que nos subas a un repositorio y nos des acceso, o nos envies un zip con el proyecto finalizado. Con la base de datos y los archivos básicos del WP, cómo la carpeta de themes para la posterior evaluación. Si crees que a parte de themes, necesitaremos algo más, puedes incluirlo en el fichero/repositorio.

Nos nos subas vendors ni node_modules, por lo tanto hemos de poder ver los assets y compilarlos si hiciese falta.

## Soporte

Por si necesitas ayuda con algún aspecto, te dejamos un listado de documentaciones que te pueden servir:

- [Wordpress](https://codex.wordpress.org/Main_Page)
- [Wordpress Repository](https://github.com/WordPress/WordPress)
- [Sass](https://sass-lang.com/)
- [Webpack](https://webpack.js.org/concepts/)
- [Docker](https://docs.docker.com/compose/)
- [Docker Desktop](https://www.docker.com/products/docker-desktop)
- [Mkcert](https://blog.filippo.io/mkcert-valid-https-certificates-for-localhost/)

Para cualquier duda o problema te puedes comunicar conmigo enviando un mail a cristian@cannactiva.com o isi@cannactiva.com
