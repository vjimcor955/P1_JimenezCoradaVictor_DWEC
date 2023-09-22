# Proyecto 1: Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente

![](img/analysis.jpg)

Durante el desarrollo de este documento se responderán las preguntras planteadas en el enunciado del Proyecto 1.

## Parte 1 - Modelos de Programación en Entornos Cliente/Servidor:

Los modelos Cliente/Servidor más comunes son los siguientes:

* **Cliente Pasivo, Servidor Pasivo**: Tanto el Cliente como el Servidor intercambian la informacion de igual manera. Ejemplo: Gateways de comunicaciones VoIP.

* **Cliente Activo, Servidor Pasivo**: La totalidad del trabajo que conlleva procesar la informacion recae en el Cliente. Ejemplo: Google Earth.

* **Cliente Pasivo, Servidor Activo**: El procesado de datos lo realiza unicamente el Servidor una vez son adquiridos por el Cliente. Ejemplo: Servidores de terminales.

* **Cliente Activo, Servidor Activo**: Tanto el Servidor como el Cliente procesan la información de igual manera. Ejemplo: Servicios de Correo Electrónico.

<br>

*Fuente: [cursosdedesarrollo.com](https://cursosdedesarrollo.com/2019/11/arquitectura-cliente-servidor/)*

## Parte 2 - Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web:

* Para interpretar JavaScript en web los navegadores incluyen un motor que permite que el codigo se ejecute. 
El compilador traduce el código fuente a bytecode de la manera más rápida posible y este bytecode es lo que el intérprete ejecuta. 
El sistema también cuenta con un «Profiler» que analiza las operaciones e identifica el código que se puede optimizar para mejorar el rendimiento. 
Por último, las secciones de bytecode son remplazadas por el código optimizado, lo que hace que el código mejore a medida que se ejecuta. 

* Los navegadores compatibles con JavaScript y sus respectivos motores son los siguientes:
    - **Firefox**: SpiderMonkey.
    - **Navegadores basados en Chromium (Chrome, Microsoft Edge, Opera)**: V8.
    - **Antiguas versiones de Opera**: Carakan.
    - **Safari**: JavaScriptCore.
    - **Internet Explorer**: Chakra intérprete de JScript.

* Los problemas de compatibilidad multi navegador de JavaScript pueden producirse al intentar utilizar funciones modernas de JavaScript en navegadores más antiguos o versiones de navegadores obsoletas.
    - Algunas de las nuevas opciones de JavaScript que no funcionan en los navegadores más antiguos incluyen Promises, que no es compatible con Internet Explorer, y las funciones Arrow, que no son compatibles con Safari o Internet Explorer.
    - Para solucionar estos problemas de compatibilidad lo recomendable es hace uso de aplicaciones como Caniuse para saber si la version de JavaScript es compatible con la version del navegador o Babel para transformar el codigo JavaScript para hacer uso de las ultimas funciones con la seguridad de que se adapta a los navegadores y versionas mas antiguas. Otras opciones son utilizar polyfills, archivos JS de terceros que funcionan de forma similar a las bibliotecas JS, o utilizar linters.

<br>

*Fuentes: [tech.tribalyte.eu](https://tech.tribalyte.eu/blog-motor-de-javascript#El_motor_de_JavaScript), [comparium.app](https://comparium.app/es/blog/cross-browser-compatibility-issues/)*

## Parte 3 - Lenguajes de Programación en Entorno Cliente:

Los lenguajes de programación en Entorno Cliente mas usados son:

* **Swift**: Swift se desarrolló por Apple en 2014 como un lenguaje de programación frontend de alto nivel para desarrollar aplicaciones para sus productos. Sus caracteristicas son las siguientes:
    - Facil de aprender.
    - Ideal para desarrollar aplicaciones en entorno Apple.
    - Soporte de red.
    - Alto rendimiento.
    - Excelente gestión de errores. 

* **React**: React fue utilizado inicialmente por Facebook para mejorar el proyecto de desarrollo web de la empresa, pero luego se convirtió en un proyecto de código abierto, a dia de hoy es usado en mas de 1,38 millones de sitios web en todo el mundo. Se caracteriza por:
    - Funcionar con JSX.
    - Una depuración rápida.
    - Contar con funciónes SEO.

* **JavaScript**: JavaScript existe desde hace décadas y, debido a su facilidad de aprendizaje, se ha convertido en uno de los lenguajes de desarrollo frontend más populares del mundo. Destaca debido a las siguientes caracteristicas:
    - Se ejecuta dentro del dispositivo del cliente, por lo que se ejecuta muy rapido usando minimos recursos.
    - Compatibilidad con otros lenguajes de programación.
    - Funciones de seguridad.
    - Cuenta con el soporte de bibliotecas que aumentan sus caracteristicas

* **CSS**: Es un lenguaje destinado a controlar el diseño de un documento web, toma la forma de un pequeño documento de texto que define la forma, apariencia y disposición de las diferentes secciones de una página web. Sus caracteristicas son:
    - Marcos CSS que permiten a los desarrolladores implementar CSS en sus diseños sin problemas.
    - Hace que HTML sea más ligero.
    - Funciones enriquecidas, lo que permite diseñar un sitio web completo desde un solo archivo.
    - Soporte del navegador.
    - Limpio y legible.

* **HTML**: HTML es el lenguaje utilizado para desarrollar sitios web, páginas web y aplicaciones basadas en la web. La simplicidad y la tolerancia a errores lo convierten en el mejor lenguaje para comenzar a programar. Se caracteriza por:
    - Fácil de aprender.
    - Es compatible con cualquier otro lenguaje de programación.
    - Pruebas y depuración rápidas.

* **Angular**: Angular se está volviendo popular entre los desarrolladores de todo el mundo, especialmente tras los avances en la función de diseño de fuentes, ya que se pueden crear páginas dinámicas (SPAS) y otras aplicaciones interactivas con funciones útiles. Sus caracteristicas son:
    - Excelente manejo de carga.
    - API RESTful, lo que permite crear interfaces de aplicaciones sin necesidad de usar bibliotecas de terceros.
    - Implementacion de AJAX
    - Estructura orientada a objetos.
    - Prueba y depuración sencillas.

* **Vue**: Vue se ha vuelto popular a lo largo de los años como un lenguaje de desarrollo de interfaz dinámico especialmente para aplicaciones móviles y de escritorio debido a características beneficiosas como el enlace de datos activo. Estas caracteristicas som:
    - Integraciones frontend.
    - Excelente para proyectos de una sola página.
    - Amplias opciones de complementos.
    - Ligero y fácil de aprender.

* **jQuery**: jQuery es un pequeño archivo JavaScript que se puede incrustar fácilmente en un proyecto web, usa varias de sus funcione sinteractivas y se puede utilizar tanto para tareas de desarrollo de frontend como de desarrollo llave en mano. Sus caracteristicas son las siguientes:
    - Admite DOM.
    - Admite efectos de animación.
    - Efectos de prueba.
    - Amplia documentación.
    - Compatible con todos los navegadores.
    - Cuenta con la función AJAX.

* **SASS**: Este marco que se lanzó en 2006 a menudo se conoce como una extensión de CSS, lo que lo hace más simple y poderoso. Se caracteriza por:
    - Altamente personalizable.
    - Aprovecha las funciones de Windows
    - Hace posible el uso de variables.
    - Funciona a la par con CSS.

* **Elm**: Elm es una buena opción para las personas que se inician en la programación frontend. A pesar de ser altamente estricto a la hora de escribir el codigo, esto ayudará a los desarrolladores noveles a escribir códigos sin errores. Sus caracteristicas son:
    - Solo puede ejecutarse en plataformas predefinidas.
    - Lectura y mantenimiento de código sencillos.
    - Admite codificación de frontend y backend.

<br>

*Fuente: [blog.back4app.com](https://blog.back4app.com/es/los-10-principales-lenguajes-de-desarrollo-del-lado-del-cliente/)*

## Parte 4 - Características de los Lenguajes de Script. Ventajas y Desventajas:

Para entender qué es lo que caracteriza a los lenguajes de Script, será de gran ayuda conocer en que se diferencia de los lenguajes de programación tradicionales. 

Tradicionalmente, el programador escribe un texto fuente que, posteriormente, se convierte en código binario. Como traductor entre ambos archivos se utiliza el llamado compilador. Por tanto, se ultilizan dos archivos: el archivo del texto fuente escrito por el programador y un archivo binario que se genera a partir de él y es el que se ejecuta directamente en el ordenador.

El lenguaje de Script, en cambio, no conlleva compilación, por lo que el segundo archivo nunca se genera. Es por ello que los programas escritos en lenguajes de Script son generalmente menos eficientes en la ejecución. A pesar de esto, y siendo consciente de esta caracteristica, los lenguajes de Script reducen la carga para el programador y aumentan la que recae en el procesador, por lo que su elección es especialmente acertada para programas pequeños y medianos.

Además de estas existen mas diferencias de los lenguajes Script sobre la progrmacion tradicional:

|            **Programación tradicional**           |   **Lenguajes de Script**   |
|:-------------------------------------------------:|:---------------------------:|
|            Específicos de la plataforma           |       Multiplataforma       |
|              Mayor cantidad de código             |      Código mas ligero      |
| Las aplicaciones creadas forman parte de un stack | Aplicaciones independientes |

* Los lenguajes de programación tradicionales son **especificos de la plataforma** mientras que los lenguajes Script son **multiplataforma**.

* Los lenguajes de programación tradicionales conllevan una **gran cantidad de codigo**, sin embargo, los lenguajes de Script permiten que los programas tengan una cantidad de código **menos intensiva**.

* Las aplicaciones creadas con lenguajes de programación tradicionales **forman parte de un stack**, al contrario de las creadas con lenguajes de Script que **son independientes**.

<br>

Tras analizar las ventajas y desventajas de ambas opciones, la conclusión es que sera el objetivo del proyecto en el que vamos a trabajar el que decirdirá cual es la mejor opción a aplicar, ya que la finalidad de estas dos opciones es bien distinta sin ser ninguna claramente mejor que otra.

<br>

*Fuentes: [kinsta.com](https://kinsta.com/es/blog/lenguajes-script/), [ionos.es](https://www.ionos.es/digitalguide/paginas-web/desarrollo-web/que-son-los-lenguajes-de-scripting/)*

## Parte 5 - Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML:

La evolución de las páginas web esta llevando a que el contenido de estas sea interactivo. Es por ello que desde hace varios años JavaScript se ha convertido en uno de los lenguajes de Script mas populares debido a la facil integración de su código con HTML5 y CSS.





<br>

*Fuente: [hostinger.es](https://www.hostinger.es/tutoriales/insertar-javascript-en-html/)*

## Parte 6 - Herramientas de Programación:

