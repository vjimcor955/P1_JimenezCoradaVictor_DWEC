---
marp: true
theme: uncover 
font-size: 35px text-align: left
---

![bg opacity:.6](img/analysis.jpg)

# Proyecto 1: Explorando los Fundamentos del Desarrollo Web en Entornos de Cliente

<br>

*Hecho por Víctor Jiménez Corada 2º DAW*

---

<!-- paginate: true -->
<!-- backgroundImage: "linear-gradient(to bottom, #00cb6f, #fff)" -->

# **Indice**

**1.** Modelos de Programación en Entornos Cliente/Servidor.
**2.** Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web.
**3.** Lenguajes de Programación en Entorno Cliente.
**4.** Características de los Lenguajes de Script. Ventajas y Desventajas.
**5.** Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML.
**6.** Herramientas de Programación.

---
# **1. Modelos de Programación en Entornos Cliente/Servidor**

Los modelos más comunes son los siguientes:

* Cliente Pasivo, Servidor Pasivo
* Cliente Activo, Servidor Pasivo
* Cliente Pasivo, Servidor Activo
* Cliente Activo, Servidor Activo

---

# **2. Mecanismos de Ejecución de Código en un Navegador Web. Capacidades y Limitaciones de Ejecución. Compatibilidad con Navegadores Web.**

Para interpretar JavaScript en web los navegadores incluyen un **motor** que permite que el codigo se ejecute, los mas usados son:
* **Firefox**: SpiderMonkey.
* **Navegadores basados en Chromium (Chrome, Microsoft Edge, Opera)**: V8.
* **Antiguas versiones de Opera**: Carakan.
* **Safari**: JavaScriptCore.
* **Internet Explorer**: Chakra intérprete de JScript.

---

Problemas de compatibilidad:

* Pueden aparecer al intentar utilizar funciones modernas de JavaScript en navegadores más antiguos o versiones obsoletas.

* Algunas de las nuevas opciones de JavaScript que no funcionan en los navegadores más antiguos incluyen Promises y las funciones Arrow.

* Para solucionar estos problemas lo recomendable es usar aplicaciones como Caniuse o Babel.

---

# **3. Lenguajes de Programación en Entorno Cliente.** 

Los lenguajes de programación en Entorno Cliente mas usados son:

* **Swift**
* **React**
* **JavaScript**
* **CSS**
* **HTML**
* **Angular**
* **Vue**
* **jQuery**
* **SASS**
* **Elm**

---

# **4. Características de los Lenguajes de Script. Ventajas y Desventajas.** 
 
|        **Programación tradicional**       |    **Lenguajes de Script**    |
|:-----------------------------------------:|:-----------------------------:|
|                 Compilador                |         Sin compilador        |
|             Programas grandes             | Programas medianos y pequeños |
|        Específicos de la plataforma       |        Multiplataforma        |
|          Mayor cantidad de código         |       Código mas ligero       |
| Las aplicaciones forman parte de un stack |  Aplicaciones independientes  |

---

# **5. Tecnologías y Lenguajes Asociados. Integración del Código con las Etiquetas HTML.** 
 
Existen dos formas de integrar código JavaScript en HTML:

* **Añadir el codigo directamente en el archivo**.

* **Añadir el código en un archivo separado**.

```
<script src="js/myscript.js"> </script>
```

---

# **6. Herramientas de Programación.**

Las herramientas de programacion usadasn en el desarrollo web en entornos de cliente pueden dividirse en varias ramas, estas son:

* **Editores de código**: Sublime text y Visual Studio Code.

* **Entornos de desarrollo integrados**: Intellij IDEA y Eclipse.

* **Control de versiones**: Git y SVN.

* **Gestores de dependencias**: Maven y NPM.

* **Herramientas de pruebas**: Selenium y Junit.

---

# Preguntas

![](img/preguntas.jpg)

---

# Bibliografía:

* Parte 1: [cursosdedesarrollo.com](https://cursosdedesarrollo.com/2019/11/arquitectura-cliente-servidor/)
* Parte 2: [tech.tribalyte.eu](https://tech.tribalyte.eu/blog-motor-de-javascript#El_motor_de_JavaScript), [comparium.app](https://comparium.app/es/blog/cross-browser-compatibility-issues/)
* Parte 3: [blog.back4app.com](https://blog.back4app.com/es/los-10-principales-lenguajes-de-desarrollo-del-lado-del-cliente/)
* Parte 4: [kinsta.com](https://kinsta.com/es/blog/lenguajes-script/), [ionos.es](https://www.ionos.es/digitalguide/paginas-web*esarrollo-web/que-son-los-lenguajes-de-scripting/)
* Parte 5: [hostinger.es](https://www.hostinger.es/tutoriales/insertar-javascript-en-html/)
* Parte 6: [tokioschool.com](https://www.tokioschool.com/noticias/herramientas-programacion/)

---

# FIN