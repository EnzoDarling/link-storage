Uno de los mejores portfolios: `http://www.rleonardi.com/interactive-resume/` :)

Criterios de calidad por Aerolab: `https://aerolab.github.io/criterios/`

Para ver compatibilidad con los navegadores `http://caniuse.com/`

# Diseño
*  [5 Patrones de diseño Responsive](https://carlosazaustre.es/blog/los-5-patrones-del-responsive-design/)
*  [Tips de Typografía legible](http://blog.invisionapp.com/typography-tips/)
*  [Sketch Tool Box](http://sketchtoolbox.com/)

### Inpiración
*  [Blog Invision](http://blog.invisionapp.com/)
*  [Dribbble](https://dribbble.com/shots/2329965-Nike90-Store)
*  [Muzli - Medium](https://medium.muz.li/ui-interactions-of-the-week-59-1d12145393f9#.egq3p05tp)
*  [Extención de Chrome - Stay inpired](https://muz.li/join/)
*  [Patrones de diseño de UI](https://www.pttrns.com/)
*  [Pinterest](https://www.pinterest.com/pin/AWcxRYRJ9r34_0cCEJsozdx6V1P4wgOVerdW3JnqrL_vE8QcmmjJm28/)
*  [Awwwards](http://www.awwwards.com/)
*  [Behance](https://www.behance.net/search?content=projects&sort=appreciations&time=week&search=ui)

### Recursos para sketch
* [sketchappsources](https://www.sketchappsources.com/all-free-sources.html)
*

# CSS
*	 [lost grid](http://lostgrid.org/docs.html)
*  [POSTCSS - lo que deberías saber](https://webdesign.tutsplus.com/es/tutorials/postcss-deep-dive-what-you-need-to-know--cms-24535)
*  [POSTCSS](http://postcss.org/)
*  [NormalizeCSS](https://necolas.github.io/normalize.css/)
*  [POSTCSS Assets](https://github.com/borodean/postcss-assets)

# Desarrollo

### Manejo de Imagenes

* [RetinaJS](http://imulus.github.io/retinajs/)
* [BeLazy](http://dinbror.dk/blazy/)
* [SRCSET](https://css-tricks.com/responsive-images-youre-just-changing-resolutions-use-srcset/)

```
@media (-webkit-min-device-pixel-ratio: 2),
(min-resolution: 192dpi) {

  .box{
    background:url('images/box-bg@2x.png') no-repeat top left;
    background-size: 200px 200px;
  }
}
```

`<img src="images/captive.png" srcset="images/captive.png 1x, images/captive@2x.png 2x">`

### Manejo Touch
* [Hammer](http://hammerjs.github.io/)


### Arquitectura de Aplicación
* [Arquitectura de un proyecto sass](https://www.sitepoint.com/architecture-sass-project/)


```
dist - todos los archivos minificados listos para producción
├── assets
│   ├── images
│   ├── js
│   ├── css
│   ├── fonts
├── index.html
|
lib or src
├── assets
├───└── stylesheets
│  		 ├── abstracts
│  		 │   ├── _functions.scss
│  		 │   ├── _mixins.scss
│  		 │   ├── _reset.scss
│  		 │   └── _variables.scss
│  		 ├── base
│  		 │   ├── _colors.scss
│  		 │   ├── _media-queries.scss
│  		 │   └── _typography.scss
│  		 ├── components
│  		 │   ├── _buttons.scss
│  		 │   ├── _inputs.scss
│  		 │   └── markdown.scss
│  		 ├── layout
│  		 │   ├── _grid.scss
│  		 │   └── _menu.scss
│  		 ├── pages
│  		 │   └── _home.scss
│  		 ├── themes
│  		 │   └── _settings.scss
│  		 ├── vendors
│  		 │   ├── normalize.css
│  		 └── components.sass
```
