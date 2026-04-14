# Fsociety

Este es el código fuente de mi **blog**. La página está basada en [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes), un tema flexible de Jekyll con dos columnas.

> **⚠️ Aviso Importante**: Aunque la documentación está en español, el contenido del blog está escrito **íntegramente en inglés**. Esto se hace por **razones profesionales y de alcance** para maximizar la visibilidad e interacción con una audiencia más amplia en el campo tecnológico.

**Compatible con Jekyll 3.5 y superiores.**

Puedes visitar mi blog [aquí](https://h4ckxel.github.io).

-----

## Ejecutar Jekyll (Pruebas Locales)

Primero, debes ejecutar `bundle install` para instalar todas las dependencias. Asegúrate de usar la última versión de `bundler` actualizando la *gem* a través de `gem install bundler`.

> **Nota**: En **macOS**, puedes instalar *Ruby* fácilmente usando [Homebrew](http://brew.sh) y ejecutando el comando `brew install ruby`.

Si `jekyll build` y `jekyll serve` generan errores, es posible que debas ejecutar Jekyll usando `bundle exec`.

En algunos casos, ejecutar los ejecutables sin `bundle exec` podría funcionar, especialmente si el ejecutable está instalado en tu sistema y no requiere *gems* que entren en conflicto con tu paquete actual.

Sin embargo, esto no es un método fiable y puede causar problemas. Incluso si parece funcionar ahora, podría fallar en el futuro o en otra máquina. Por lo tanto, se recomienda la siguiente forma:

```bash
$ bundle exec jekyll build

$ bundle exec jekyll serve
```

> **Nota**: Al realizar pruebas localmente, recomiendo usar `url: "http://localhost:4000"` para que las rutas apunten a las páginas y recursos locales. Lo ideal sería usar múltiples archivos de configuración con `bundle exec jekyll serve --config _config.yml,_config.dev.yml` para aplicar ajustes específicos de desarrollo.

-----

## Créditos

### Creador

**Michael Rose**

  - [https://mademistakes.com](https://mademistakes.com)
  - [https://twitter.com/mmistakes](https://twitter.com/mmistakes)
  - [https://github.com/mmistakes](https://github.com/mmistakes)

### Iconos e Imágenes de Demostración:

  - [The Noun Project](https://thenounproject.com) -- Garrett Knoll, Arthur Shlain y [tracy tam](https://thenounproject.com/tracytam)
  - [Font Awesome](http://fontawesome.io/)
  - [Unsplash](https://unsplash.com/)

### Otros:

  - [Jekyll](http://jekyllrb.com/)
  - [jQuery](http://jquery.com/)
  - [Susy](http://susy.oddbird.net/)
  - [Breakpoint](http://breakpoint-sass.com/)
  - [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/)
  - [FitVids.JS](http://fitvidsjs.com/)
  - [GreedyNav.js](https://github.com/lukejacksonn/GreedyNav)
  - [Smooth Scroll](https://github.com/cferdinandi/smooth-scroll)
  - [Gumshoe](https://github.com/cferdinandi/gumshoe)
  - [jQuery throttle / debounce](http://benalman.com/projects/jquery-throttle-debounce-plugin/)
  - [Lunr](http://lunrjs.com)

-----

## Licencia

La Licencia MIT (MIT)

Copyright (c) 2013-2020 Michael Rose y colaboradores

Se concede permiso, de forma gratuita, a cualquier persona que obtenga una copia
de este software y de los archivos de documentación asociados (el "Software"), para tratar
el Software sin restricción, incluyendo sin limitación los derechos
de uso, copia, modificación, fusión, publicación, distribución, sublicencia y/o venta
de copias del Software, y para permitir a las personas a las que se les proporcione el Software
hacerlo, sujeto a las siguientes condiciones:

El aviso de copyright anterior y este aviso de permiso se incluirán en todas
las copias o partes sustanciales del Software.

EL SOFTWARE SE PROPORCIONA "TAL CUAL", SIN GARANTÍA DE NINGÚN TIPO, EXPRESA O
IMPLÍCITA, INCLUYENDO PERO NO LIMITADO A LAS GARANTÍAS DE COMERCIALIZACIÓN,
IDONEIDAD PARA UN PROPÓSITO PARTICULAR Y NO INFRACCIÓN. EN NINGÚN CASO LOS
AUTORES O TITULARES DEL COPYRIGHT SERÁN RESPONSABLES POR NINGUNA RECLAMACIÓN, DAÑOS U OTRAS
RESPONSABILIDADES, YA SEA EN UNA ACCIÓN DE CONTRATO, AGRAVIO O DE OTRO TIPO, QUE SURJAN DE,
FUERA DE O EN CONEXIÓN CON EL SOFTWARE O EL USO U OTRAS OPERACIONES EN EL
SOFTWARE.

Minimal Mistakes incorpora iconos de [The Noun Project](https://thenounproject.com/)
creadores Garrett Knoll, Arthur Shlain y tracy tam.
Los iconos se distribuyen bajo Creative Commons Attribution 3.0 United States (CC BY 3.0 US).

Minimal Mistakes incorpora [Font Awesome](http://fontawesome.io/),
Copyright (c) 2017 Dave Gandy.
Font Awesome se distribuye bajo los términos de la [SIL OFL 1.1](http://scripts.sil.org/OFL)
y [Licencia MIT](http://opensource.org/licenses/MIT).

Minimal Mistakes incorpora fotografías de [Unsplash](https://unsplash.com).

Minimal Mistakes incorpora [Susy](http://susy.oddbird.net/),
Copyright (c) 2017, Miriam Eric Suzanne.
Susy se distribuye bajo los términos de la [Licencia BSD de 3 cláusulas "Nueva" o "Revisada"](https://opensource.org/licenses/BSD-3-Clause).

Minimal Mistakes incorpora [Breakpoint](http://breakpoint-sass.com/).
Breakpoint se distribuye bajo los términos de las [Licencias MIT/GPL](http://opensource.org/licenses/MIT).

Minimal Mistakes incorpora [FitVids.js](https://github.com/davatron5000/FitVids.js/),
Copyright (c) 2013 Dave Rubert y Chris Coyier.
FitVids se distribuye bajo los términos de la [Licencia WTFPL](http://sam.zoy.org/wtfpl/).

Minimal Mistakes incorpora [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/),
Copyright (c) 2014-2016 Dmitry Semenov, [http://dimsemenov.com](http://dimsemenov.com).
Magnific Popup se distribuye bajo los términos de la Licencia MIT.

Minimal Mistakes incorpora [Smooth Scroll](http://github.com/cferdinandi/smooth-scroll),
Copyright (c) 2019 Chris Ferdinandi.
Smooth Scroll se distribuye bajo los términos de la [Licencia MIT](http://opensource.org/licenses/MIT).

Minimal Mistakes incorpora [Gumshoejs](http://github.com/cferdinandi/gumshoe),
Copyright (c) 2019 Chris Ferdinandi.
Smooth Scroll se distribuye bajo los términos de la [Licencia MIT](http://opensource.org/licenses/MIT).

Minimal Mistakes incorpora [jQuery throttle / debounce](http://benalman.com/projects/jquery-throttle-debounce-plugin/),
Copyright (c) 2010 "Cowboy" Ben Alman.
jQuery throttle / debounce se distribuye bajo los términos de la [Licencia MIT](http://opensource.org/licenses/MIT).

Minimal Mistakes incorpora [GreedyNav.js](https://github.com/lukejacksonn/GreedyNav),
Copyright (c) 2015 Luke Jackson.
GreedyNav.js se distribuye bajo los términos de la [Licencia MIT](http://opensource.org/licenses/MIT).

Minimal Mistakes incorpora [Jekyll Group-By-Array](https://github.com/mushishi78/jekyll-group-by-array),
Copyright (c) 2015 Max White [mushishi78@gmail.com](mailto:mushishi78@gmail.com).
Jekyll Group-By-Array se distribuye bajo los términos de la [Licencia MIT](http://opensource.org/licenses/MIT).

Minimal Mistakes incorpora [@allejo's Pure Liquid Jekyll Table of Contents](https://allejo.io/blog/a-jekyll-toc-in-liquid-only/),
Copyright (c) 2017 Vladimir Jimenez.
Pure Liquid Jekyll Table of Contents se distribuye bajo los términos de la [Licencia MIT](http://opensource.org/licenses/MIT).

Minimal Mistakes incorpora [Lunr](http://lunrjs.com),
Copyright (c) 2018 Oliver Nightingale.
Lunr se distribuye bajo los términos de la [Licencia MIT](http://opensource.org/licenses/MIT).