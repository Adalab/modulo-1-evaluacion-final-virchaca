![Ejercicio Evaluacion Final](http://beta.adalab.es/modulo-1-evaluacion-final-virchaca/)

# Ejercicio Modulo I - _Virginia_

Ahoy! Este es nuestro primer proyecto individual dentro del Boot Cap de desarrolladoras web que estamos realizando en **Adalab**. 

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

A la hora de estructurar el proyecto, dentro de mis archivos  _HTML_ y _SCSS_ he creado los siguientes parciales:

## Parciales en HTML ( en la carpeta La carpeta `src/` --> `html/` --> `partials/`):
- Header
- Main:
  · section.hero
  · section-sport
  · section school
     + articleChildren
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

Despues de dar formato y estilo al proyecto, lo he publicado en GitHub Pages, mediante el comando:

un servicio de alojamiento de sitio estático que toma archivos HTML, CSS y JavaScript directamente desde un repositorio en GitHub, opcionalmente ejecuta los archivos a través de un proceso de complilación y publica un sitio web.

```bash
npm run deploy
```
De manera que  las profesaoras tengan acceso al mismo para poder evaluarlo.
