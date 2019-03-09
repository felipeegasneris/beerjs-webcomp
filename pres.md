title: BeerJS
author:
  name: Felipe Egas Neris
  email: felipe.egas.neris@hotmail.com
output: basic.html
controls: true
theme: juanbrujo/cleaver-beerjs

--

# Webcomponents en el 2018
## BeerJS noviembre 2018

--

### ¿Qué es un webcomponent?
* lo presenta un ingeniero de Google, Alex Russell
* permite crear nuevas etiquetas HTML
* permite encapsular js y css
* tenemos componentes, ¡independientes de frameworks!

--
### Las especificaciones que ocupa
* **Custom Elements**:  Describe el método para permitir a los desarrolladores definir y usar nuevos tipos de elementos del DOM en un documento HTML.

* **HTML Templates**: Te permite definir fragmentos de HTML que pueden ser clonados o insertados en un documento.

* **Shadow DOM**: Esta especificación determina cómo tener múltiples árboles de elementos en una sola jerarquía, cómo estos árboles interactúan entre ellos siendo independientes y permitiendo una mejor composición.


--
### Las especificaciones que ocupa

* **ES Modules** : Es el estándar de ECMAScript para importar módulos Javascript. Permite tanto la carga síncrona como asíncrona de los mismos, los puede analizar estáticamente y, por lo tanto, nos ofrecerá una carga más óptima de nuestras dependencias.

* **HTML Imports**: Era una forma de importar documentos HTML en otros documentos HTML. Digo era ya que es una característica abandonada. Hay un interesante debate sobre empezar de cero una nueva característica llamada HTML Modules, siguiendo la filosofía de los ES Modules de Javascript.
--

### Mucho blabla, ¿y si mejor creamos uno?

![](https://i.imgur.com/Yy6XRwP.jpg)

--
### Librerias que nos facilitaran la vida

* [Polymer](https://www.polymer-project.org/)
* [LitElement](https://github.com/Polymer/lit-element)
* [Stencil](https://stenciljs.com/)

--
### Mmmm se ve bueno pero, ¿Cual es el soporte que tienen?
![](https://i.imgur.com/V896V0c.png)

* **Con polyfills podemos llegar a aproximadamente un 90% de soporte a navegadores*

-- 
### Ya pero yo tengo mis desarollos en [*inserte libreria de moda aquí*], ¿puedo usar webcomponents?

* Sí la mayoria de los frameworks mas ultilizados tienen un 100% de compatibilidad con webcomponents, esto se puede ver en [https://custom-elements-everywhere.com/](https://custom-elements-everywhere.com/), bueno exceptuando por unos pocos como *React* :(

![](https://i.imgur.com/6ZU8Qdn.png)
--
### Gracias por su atención

![](https://i.imgur.com/UXCYM0w.jpg)
