# <p align="center"> React-CSV-file-reader </p>

<p align="center"> Francisco D. Salcedo C. a01633010 </p>
<p align="center"> Gerardo Gutierrez Paniagua a01029422</p> 
<p align="center"> Mateo Herrera Lavalle a01751912</p> 
<p align="center"> TC2007B</p> 
<p align="center"> 24 de agosto del 2022</p> 


## Aplicación

Esta aplicación de react lee archivos CSV y presenta la información dentro de estos en tablas. Específicamente, la aplicación lee datos sobre estudiantes contenidos en un archivo CSV. Posteriormente, la aplicación muestra la información de estos estudiantes en dos tablas. La primera contiene la información original y la segunda contiene información que fue modificada para tener un diferente formato.

De igual manera, dentro de la App se realizaron diversas pruebas con JEST para verificar su correcto funcionamiento.


## Marco Teórico


Existen distintos tipos de pruebas en el ciclo de vida y desarrollo de software. Estas se realizan en diferentes periodos y sujetas condiciones que detonen la necesidad de realizar dicha prueba. Entre ellas existen,


* **Pruebas locales.**

  Estas pruebas ocurren durante el desarrollo - cuando se implementan cambios en los componentes y se quiere observar el nuevo o extendido comportamiento.
* **Pruebas de integración.**

  Estas pruebas aseguran que los componentes del software funcionen correctamente y operen juntos.
* **Pruebas alfa.**
  
  Las pruebas alfa (alpha testing) ocurren cuando el producto ha alcanzado un estado de completitud suficiente para ser revisado por un equipo de calidad antes de ser lanzado a pruebas con los clientes.
* **Pruebas de regresión.**

  Las pruebas de regresión ocurren cuando se añaden nuevos componentes al producto - este tipo de pruebas valida que cada componente funcione de la misma manera antes de que el nuevo componente haya sido introducido.
* **Pruebas dinámicas de validación.**

  En estas pruebas se tiene que ejecutar el software para posteriormente evaluar e inspeccionar que se cumplan los requisitos. Probar con el producto “final” directo.
* **Pruebas bajo condiciones frontera.**

  Las pruebas bajo condiciones frontera (stress testing) ocurren cuando se quiere analizar el comportamiento del producto bajo condiciones poco favorables o de estrés para el sistema - condiciones que aunque difíciles de alcanzar son posibles: desgaste de memoria, requerimiento excesivo de disco, entre otros.

## Herramientas de Prueba

* **Selenium:** Automatiza la ejecución de pruebas en lenguajes populares como c + +, java, perl, php, python, y otros más similares. Permite bajo ciertas versiones la ejecución remota, sin embargo su integración a un proyecto puede resultar laborioso. 
* **TAST:** Automatiza efectivamente pruebas de software en base a diagramas uml del proyecto, puede implementar o integrar otras herramientas como selenium o appium, todo utilizando una mínima curva de aprendizaje. 
* **JEST:** Este marco de prueba es particularmente para javascript utilizando React o algún otro framework de JS, es fácil de instalar al proyecto que se está desarrollando. También es compatible con typescript y se pueden implementar fácilmente métricas o simulacros de temporizador. 
* **Appium:** Esta herramienta está orientada a la ejecución de pruebas de aplicaciones móviles, donde se pueden implementar otras herramientas como selenium grid para evaluaciones paralelas o remotas.
* **Katalon Studio:** Para el uso de Katalon no se requieren habilidades de programación pero puede complicarse la implementación de ciertas pruebas que se quieran hacer. 

## Pruebas utilizando una app de React (JEST)
Para la aplicación de pruebas de la actividad 4:Desarrollo de aplicaciones móviles, se seleccionó Jest por su compatibilidad con javascript y el framework de React, además de su implementación sencilla dentro del mismo proyecto.

Las pruebas implementadas constan de evaluar el funcionamiento de cada función involucrada en cumplir el requisito de convertir archivos de un formato a otro. Siendo entonces un total de 4 funciones cada una perteneciente a uno de los campos a cambiar en el formato del archivo csv. 

Específicamente, se busca verificar que el cambio de formato suceda correctamente comparando el resultado obtenido del programa con un arreglo de los datos de prueba ya formateados. Esta comparación es estricta pues el cambio de formato no puede variar si se quiere que funcione de manera adecuada todo el proyecto. 

También, se comprobó que los componentes estuvieran pasando por el proceso de render y se pudiera visualizar la información de la manera que se buscaba. 


## Referencias

Joshi, V. (20 de enero de 2020). “Jest como marco de prueba de JavaScript popular”. 

  Recuperado desde https://cynoteck.com/es/blog-post/jest-as-a-popular-javascript-testing-framework/

Ciberninjas. (S.F.). “11 Mejores Herramientas de automatización de pruebas para interfaces de usuario”.
  
  Recuperado desde https://ciberninjas.com/10-mejores-herramientas-pruebas-ui/
