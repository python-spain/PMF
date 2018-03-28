# PMF - Preguntas Más Frecuentes (FAQ)

Grupos de Telegram: 

* Temáticos: [Python España](https://t.me/PythonEsp) - [Python Científico](https://t.me/python_cientifico) - [Django España](https://t.me/DjangoEsp) - [Flask España](https://t.me/FlaskEsp) - [Python-EDU España](https://t.me/PythonEsp_Edu)

* Territoriales: [Alicante](https://t.me/python_alc) - [Canarias](https://t.me/pythoncanarias) - [Castilla y León](https://t.me/PyCyL) - [Extremadura](https://t.me/ExtrePython) (canal) - [Girona](https://t.me/pygrn) - [Granada](https://t.me/pythongranada) - [Valencia](https://t.me/python_vlc) - [Vigo](https://t.me/joinchat/DdKphwfW2-qqPf5JsVGjCg) 

Licencia: [Creative Commons 0 (CC0)](LICENSE)

**Listado de preguntas frecuentes**

* [¿Cuál es el mejor editor/IDE para Python?](#cu%C3%A1l-es-el-mejor-editoride-para-python)
* [¿Qué curso/libro recomendáis para empezar?](#qu%C3%A9-cursolibro-recomend%C3%A1is-para-empezar)
* [No me funciona un programa. Estoy atascado. ¿Alguien me puede ayudar?](#no-me-funciona-un-programa-estoy-atascado-alguien-me-puede-ayudar)
* [¿Qué librería/*framework* recomendáis para...?](#qu%C3%A9-librer%C3%ADaframework-recomend%C3%A1is-para)
  * [Aplicaciones gráficas (GUI)](#aplicaciones-gráficas)
  * [Extraer información de la web](#extraer-información-de-la-web)
* [Dicen por ahí que Python es lento...¿es cierto?](#dicen-por-ah%C3%AD-que-python-es-lentoes-cierto)
* [¿Puedo publicar una oferta de trabajo?](#puedo-publicar-una-oferta-de-trabajo)

----

## ¿Cuál es el mejor editor/IDE para Python?

Cada persona tiene sus preferencias, experiencia, sistema operativo, necesidades, etc. Es importante sentirse cómodo con la herramienta que más vas a utilizar. Por lo tanto, en lugar de basarte en la opinión subjetiva de los demás (con otras preferencias, experiencias, ...), te resultará mucho más útil escoger uno o varios (de entre los listados que te damos a continuación) y probar durante un tiempo cada una. *Solo tú puedes contestar a la pregunta*.

En [Full Stack Python](https://www.fullstackpython.com/) se recopila una buena selección de direcciones sobre [entornos de desarrollo](https://www.fullstackpython.com/development-environments.html) (en inglés). También tienes una completa [tabla comparativa](https://www.reddit.com/r/learnpython/wiki/ide) en *reddit* que te puede servir de guía para escoger.

En la misma [wiki de Python.org](https://wiki.python.org/) hay un par de listados exhaustivos sobre editores e IDEs:

* [Editor de texto](https://wiki.python.org/moin/PythonEditors)
* [IDEs](https://wiki.python.org/moin/IntegratedDevelopmentEnvironments)

## ¿Qué curso/libro recomendáis para empezar?

Depende de tu situación. ¿Ya sabes programar en algún lenguaje? ¿Tienes "inglés nivel medio"?

Si no tienes conocimientos de programación, puedes empezar por estos tutoriales/libros:

* [Tutorial oficial de Python](http://docs.python.org.ar/tutorial/3/) (traducción de Python Argentina)
* [Tutorial de Django Girls](https://tutorial.djangogirls.org/es/)
* [Introducción a la programación con Python 3](http://dx.doi.org/10.6035/Sapientia93) (Universitat Jaume I)

Python Argentina también dispone de una página con más recursos recopilados: [Aprendiendo Python](http://www.python.org.ar/aprendiendo-python/).

Si tienes conocimientos básicos de programación (en algún otro lenguaje) te recomendamos:

* [Python 3 para impacientes](http://python-para-impacientes.blogspot.com/p/indice.html)

En caso de no tener problema con leer en inglés, la oferta es mucho mayor:

* [Python's *original* tutorial](https://docs.python.org/3/tutorial/)
* [Learning Python](http://docs.python-guide.org/en/latest/intro/learning/) - a section from [The Hitchhiker’s Guide to Python](http://docs.python-guide.org/) (a very good and complete list of resources)

## No me funciona un programa. Estoy atascado. ¿Alguien me puede ayudar?

Si es de las primeras veces que preguntas en un foro, puede interesarte saber [cómo hacer preguntas](http://www.sindominio.net/ayuda/preguntas-inteligentes.html) y, una vez te decidas a preguntar, nos cuentes también [qué has intentado](https://medium.com/@unrob/que-has-intentado-12b31d36bc89) para que funcione tu código. Para que no vayamos a ciegas, es recomendable que pegues tu código en una de las webs de abajo y compartas la URL generada en el canal:

   * https://pastebin.com/
   * https://bpaste.net/
   * https://repl.it/languages/python3
   * https://trinket.io/python
   * https://github.com/
   * https://gitlab.com/
   * https://bitbucket.org/

## ¿Qué librería/*framework* recomendáis para...?

  Antes de preguntar por una librería o *framework* puedes echar un vistazo a las alternativas que hay en el ámbito de tu problema. Un recurso muy interesante para poder conocer dichas alternativas es [awesome-python](https://github.com/vinta/awesome-python). Verás que cubre muchos ámbitos. Hay listas más específicas si tu pregunta trata de [Django](https://gitlab.com/rosarior/awesome-django), [Flask](https://github.com/humiaozuzu/awesome-flask) o [Pyramid](https://github.com/uralbash/awesome-pyramid).

  Intenta hacer una pregunta concreta. No es buena idea preguntar *¿qué es mejor X o Y?*. Sin información, la respuesta de cualquier participante será subjetiva. Matiza cuál es el problema que quieres resolver para que podamos ayudarte en la recomendación.
  
### Aplicaciones gráficas (GUI)

Las principales opciones que hay ahora mismo (Marzo 2018) en Python para crear aplicaciones gráficas son:

Framework Python | Descripcion | Framework Base | Diseñador Visual de Interfaz | Licencia | Última Version Estable (Marzo'18) |
:---: | :---| :---: | :---: | :---: | :---: |
[Tkinter](https://docs.python.org/3/library/tk.html) | Framework multiplataforma base incluido en Python por defecto en la librería estándar.  | [Tcl/Tk](http://www.tcl.tk/) |  | [Python License](https://docs.python.org/3/license.html) |
[PyQt](https://riverbankcomputing.com/software/pyqt/intro) | Framework multiplataforma muy popular basado en Qt. Para uso comercial requiere la compra de una licencia (Ver Licencia). | [Qt](https://www.qt.io/) | [Qt Creator](https://www.qt.io/ide/) | [GNU GPL v3](https://www.gnu.org/licenses/gpl-3.0.en.html) y [Riverbank Commercial License](https://www.riverbankcomputing.com/commercial/pyqt)| PyQt5 |
[PySide](http://wiki.qt.io/PySide) | Framework multiplataforma basado en Qt, pero con una licencia menos restrictiva. No soporta Qt5 pero está en desarrollo la versión 2 que si lo hace. | [Qt](https://www.qt.io/) | [Qt Creator](https://www.qt.io/ide/) | [LGPL](https://www.gnu.org/licenses/lgpl-3.0.en.html) | 1.2.4 (Qt4) |
[wxPython](https://www.wxpython.org/) | Framework multiplataforma bastante popular basado en wxWidgets que tiene como principal ventaja que los componentes son nativos y por lo tanto su apariencia es igual a la del SO en el que se usan. | [wxWidgets](https://www.wxwidgets.org/) | [wxGlade](http://wxglade.sourceforge.net/) o [wxFormBuilder](https://github.com/wxFormBuilder/wxFormBuilder) | [wxWindows Library Licence](https://www.wxpython.org/pages/license/) | 4.0.1 |
[Python GTK+](https://python-gtk-3-tutorial.readthedocs.io/en/latest/index.html) | Framework multiplataforma basado en GTK+3. (PyGTK es la versión antigua y usa GTK+2) | [GTK+](https://www.gtk.org/) | [glade](https://glade.gnome.org/) | [LGPL](https://www.gnu.org/licenses/lgpl-3.0.en.html) | 3.4 |
[Kivy](https://kivy.org/) | Framework multiplataforma diseñado para funcionar además de en entornos de escritorio, en Android o IOS. |  | [Kivy Designer](https://kivy-designer.readthedocs.io/en/latest/) | [MIT license](https://en.wikipedia.org/wiki/MIT_License) | 1.10 |
[Toga](https://pybee.org/project/projects/libraries/toga/) | Framework multiplataforma orientado a desarrollo móvil con widgets nativos (en linux requiere GTK+3). Está en desarrollo. |  |  | [New BSD License](https://en.wikipedia.org/wiki/BSD_licenses) | 0.3 |
[pywebview](https://github.com/r0x0r/pywebview) | Es un wrapper de un componente webview que se basa en distintos frameworks dependiendo de la plataforma en la que se instala. Al ser un componente webview, el render lo decide el SO, por lo que en windows (por ejemplo) estás atado a Internet Explorer. | [Depende del SO](https://github.com/r0x0r/pywebview#dependencies) |  | [New BSD License](https://en.wikipedia.org/wiki/BSD_licenses) | 1.8


Si quieres ver todas las opciones, puedes leer el [listado de GUIs](https://docs.python.org/3/faq/gui.html) en la web de Python así como [herramientas de diseño](https://wiki.python.org/moin/GuiProgramming#GUIDesignToolsandIDEs) en la wiki de Python.

### Extraer información de la web

Básicamente tienes dos opciones:

  * Usar [Requests](http://docs.python-requests.org) para el acceso y [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) para la extracción.
  * Usar el *framework* [Scrapy](https://scrapy.org/).
  
  También puede resultarte de ayuda el capítulo de [Web scraping](https://automatetheboringstuff.com/chapter11/) del libro [Automate the boring stuff](https://automatetheboringstuff.com/) en el que también se utiliza [Selenium](http://www.seleniumhq.org/).

## Dicen por ahí que Python es lento...¿es cierto?

  Es posible que te hayan contado *cosas malas* de Python pero ¿te crees todo lo que te dicen? Te recomendamos que leas un par de páginas para formarte una idea más realista:
  
  * [Yes, Python is Slow, and I Don’t Care](https://hackernoon.com/yes-python-is-slow-and-i-dont-care-13763980b5a1)
  * [10 Myths of Enterprise Python](https://www.paypal-engineering.com/2014/12/10/10-myths-of-enterprise-python/)

## ¿Puedo publicar una oferta de trabajo?

  Se pueden enviar ofertas de trabajo al [grupo de Telegram](https://t.me/PythonEsp) y a la [lista de correo general de la asociación Python España](general@lists.es.python.org) mientras sigas estas reglas para publicarlas: https://lists.es.python.org/pipermail/general/2016-October/003294.html

  Además, si tu empresa vende productos y servicios basados en Python, o utiliza Python internamente, puedes añadirla al listado de [empresas python-friendly en España](https://github.com/python-spain/empresas). De esta manera estarás dando visibilidad al uso de Python en la industria del software en España.
