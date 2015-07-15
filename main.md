* * *

# DESCRIPCION #

# ¿Que es **IMK**? #

**IMK** significa **I**nclusive **M**ar**k**up Language. Esto es: Un lenguaje de marcado ligero que pretende ser inclusivo. Le he añadido la coletilla de "_Yet another markdown flavour?_" por un lado haciéndo un guiño a perl, por otro lado constatand o que se trata de un _flavour_ de [**Markdown**](http://daringfireball.net/projects/markdown/). Con _flavour_ me refiero a una variante del desarrollo original, que le añade o le personaliza alguna característica.

# ¿Porqué otro _flavour_ más de **markdown**? #

Adoro **Markdown**. Desde que lo conozco he ido uśandolo cada vez para más cosas, para todo lo que puedo. Es una forma sencilla y clara de formatear textos, haciéndolos más legibles pero sin molestar a la lectura, es muy natural.  
Al usarlo para muchos y variados fines, he ido detectando algunas carencias. Eso me ha echo investigar los diferentes _flavours_, y ver si me proporcionaban lo que necesitaba puntualmente.  
Uno de los problemas de esto es que un determinado _flavour_ puede no ser compatible con el resto de herramientas que usas, como el editor, el conversor o el render, porque usan **Markdown original** o un _flavour_ concreto.  
En este proceso me he familiarizado con **Markdown original**, [**Markdown 2**](http://markdown2.github.io/site/), y con _flavours_ como [**extra**](https://michelf.ca/projects/php-markdown/extra/), [**github**](https://help.github.com/articles/github-flavored-markdown/), [**stackedit**](https://stackedit.io/Welcome%20document.pdf) o [**pandoc**](http://pandoc.org/demo/example9/pandocs-markdown.html). Todos ellos tienen aportes muy buenos, pero volvemos al tema de las incompatibilidades. Son exclusivos entre ellos.  
Es por ello que en este _flavour_, pretendo aunar todos esos puntos fuertes, extenderlos y adaptarlos siguiendo la [filosofía de **Markdown original**](http://daringfireball.net/projects/markdown/syntax#philosophy).

# ¿Porqué **markdown** y no otro lenguaje de marcado ligero, más completo? #

Porque conozco y me desenvuelvo bien con **Markdown**; me resulta muy familiar. Además ahora es notablemente popular, gracias a su uso en comunidades de desarrolladores como Github. Por lo cual hay ya bastante gente que lo conoce, y hay una gran variedad de herramientas que lo interpretan. Por ello es más sencillo adaptar las múltiples herramientas existentes, que crear una nueva.

# ¿ Qué aporta este _flavour_? #

Compatibilidad con otros _flavours_, opciones de formateo más elaboradas, misma filosofía basada en legibilidad, inclusión de metadatos, renders específicos de gráficos, diagramas, plugins...

## Tus textos, como tú quieras que se vean. ##

En **IMK** se pueden incluir metadatos para que incluso con entornos personalizados, el texto renderizado mantenga el aspecto que tu quieres. Estos metadatos no molestarán al manejo del texto.

## Una única herramienta, todo el poder. ##

Puede utilizarse para los usos ordinarios y simples que le das al **Markdown original**, pero puede proveerte de características de formateo y maquetación, como para escribir complejas tesis doctorales... Sin límites, sencillo y legible.

## Absolutamente libre. ##

Amamos lo libre, también literalmente. Por ello hemos considerado que **IMK** debe estar bajo licencia GPLv3. De esta manera todos pueden contribuir, personalizar, adaptar y hacer que crezca. ¡Involúcrate!

## Exporta e importa sin perder información. ##

Gracias al sistema de metadatos, se puede importar otros formatos de marcado a **IMK** y no se perderá información. ¡Incluso si **IMK** no es compatible con alguna funcionalidad! Si después vuelves a exportar, tus cambios hechos con **IMK** estarán junto al contenido no interpretado por **IMK**.

* * *

# SINTAXIS #

[^asdf] cita al pie de página
[^$asdf] cita bibliográfica
[^_asdf] cita al pie de objeto (cuadro de texto, imagen, etc.)
[^~asdf] nota al pie
{asdf} versalitas
<<asdf>> comillas angulares -> smartypants
(c) copyright -> smartypants
*[asdf] abreviación
^asdf^ superindice
~asdf~ subindice
~~asdf~~ tachado
|asdf texto en línea
]asdf cuadro de texto
