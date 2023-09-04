
# Ejercicio Modulo I - _Virginia Alvarez Perez_

Ahoy! Este es nuestro primer proyecto individual dentro del BootCamp de desarrolladoras web que estamos realizando en **Adalab**. 

El proyecto consiste en crear una página web de _vuelta al cole_ en los tres formatos más habituales:

   - Móvil
   - Tablet
   - Desktop

Para ello usaremos diferentes tipos de lenguaje, empezando por **HTML** para crear la estructura del proyecto, y siguiendo con **SASS** para darle estilo. Y nos valdremos del _Starter Kit_ proporcionado por nuestras profes de Adalab. Este Kit incluye un motor de plantillas HTML, el preprocesador SASS y un servidor local y muchas cosas más. El Kit nos ayuda a trabajar más cómodamente, nos automatiza tareas.

En el Kit hay 3 tipos de ficheros y carpetas:

- Los ficheros que están sueltos en la raíz del repositorio, como gulpfile.js, package.json... Son la configuración del proyecto y no necesitamos modificarlos.
- La carpeta `src/`: son los ficheros de nuestra página web, como HTML, CSS, ...
- Las carpetas `public/` y `docs/`, que son generadas automáticamente cuando arrancamos el proyecto. El Kit lee los ficheros que hay dentro de `src/`, los procesa y los genera dentro de `public/` y `docs/`.

He iniciado el proyecto mediante el siguiente comando para instalar las dependencias locales:
```bash
npm install
```
Y posteriormente, he arrancado el proyecto mediante el comando:
```bash
npm start
```
**El proyecto hay que arrancarlo cada vez que nos ponemos a programar.**

En la parte de HTML he estructurado el proyecto, dividiendo el body en diferentes partes, 3 principales, **header**, **main** y **footer**. Dentro de main, las más extensa, he hecho varias secciones, _hero_, con la imagen de fondo y los titulos principales; _sport_, donde se hace una breve introducción de la tienda donde adquirir productos para los estudiantes; y por último _school_, donde se ven unas imagenes de estudiantes con algunas opciones de productos.
En cada apartado he incluido unos botones de compra (comprar y empezar ahora) para facilitar al usuario el trámite de comprar los productos. Y unos botones _scroll_ para acceder diretamente desde el principio de la pagina al final, y desde el final, al principio.
En el footer he hecho varias secciones con listas de links e iconos que redireccionan al usuario a sus correspondientes paginas web, y por último, he incluido el copyright y eslogan de " we love run", con un pequeño corazon verde representando la palabra _love_.

A la hora de estructurar el proyecto, dentro de mis archivos  _HTML_ y _SCSS_ he creado los siguientes parciales:

## Parciales en HTML ( en la carpeta La carpeta `src/` --> `html/` --> `partials/`):

- Header
- Main:
  + section.hero
  + section-sport
  + section school
     - articleChildren
- footer

## Parciales en SASS ( en la carpeta La carpeta `src/` --> `scss/`):
`scss/` --> `core/`:

 - reset (para establecer unas medidas standard de las propiedades margin, padding y box-sizing de la página)
 - variables (definen todas las propiedades de fuente y color utilizadas en el proyecto)

`scss/` --> `layout/`:

- header
- main
- hero
- sport
- school
- footer

Y he vinculado todos los parciales con sus correspondientes etiquetas, para el correcto funcionamiento de la página web:
 * En HTML:
   
```bash
<include src="**url del partial correspondiente**"></include>
```
 * En SCSS:

```bash
@import '**url del partial correspondiente**'
```

Despues de dar formato y estilo al proyecto, lo he publicado en GitHub Pages, mediante el comando:

```bash
npm run deploy
```

GitHub Pages un servicio de alojamiento de sitio estático que toma archivos HTML, CSS y JavaScript directamente desde un repositorio en GitHub, opcionalmente ejecuta los archivos a través de un proceso de complilación y publica un sitio web. De manera esta manera las profesoras tengan acceso a mi proyecto para poder evaluarlo.

Os dejo aqui el enlace a la pagina para que podais echarle un vistazo!

[Ejercicio Evaluacion Final] (http://beta.adalab.es/modulo-1-evaluacion-final-virchaca/)
