# Software Testing desde Cero : MasterClass todo en 1 (2021)

## Section 1

### Video 1

En este curso aprenderé todo lo que necesitas sobre las pruebas de software, partiendo de los fundamentos del testing pasando por la metodologías de pruebas actuales en proyectos ágiles con SCRUM como también todo sobre automatización usando *CYPRESS* y *SELENIUM IDE*.

---

### Video 2

Recomendaciones para el curso.

---

## Section 2

### Video 3

#### **¿Qué es el *software testing* y por qué es tan importante?**

Todas las aplicaciones que usamos a diario tienen errores (también llamados **bugs**). Plataformas online como Facebook, Instagram, YouTube, corrigen una cantidad de bugs y esto se debe a constantes cambios en las reglas de negocio, errores de programación. Los errores o defectos en la aplicación impactan negativamente en el funcionamiento de la aplicación. El testing de software contribuye a que los usuarios persivan la menor cantidad de fallas y que tengan una mejor experiencia.
**Definición**  
El **Testing** es una disciplina en la ingeniería de software que se realiza mediante una metodología de verificación y validación cuyo principal objetivo es localizar errores en un **software** para ser corregidos por el equipo de desarrollo y de esta manera ***aumentar la confianza en el nivel de calidad del sistema***.  
La importancia del software radica en que es mucho mejor y más barato la detección de errores temprano en el proceso de desarrollo. No solo afecta económicamente si no que afecta la reputación de la empresa.

---

### Video 4

#### ***Habilidades de un tester***

- **Pensamiento lógico**  
Debe saber desglosar un sistema en unidades más pequeñas para poder crear casos de prueba. Debe saber hacer un análisis funcional de la aplicación y saber cómo puede separar sus funciones, saber para qué sirve cada una y qué impacto tiene cada opción para el negocio. Saber pensar desde el punto de vista del negocio y del usuario.
- **Muy buena comunicación**  
Excelente comunicación verbal y escrita para comunicar los errores y documentarlos. Como testers estamos en constante comunicación con diferentes personas como desarrolladores, analistas de requisitos o el dueño del producto. Debes ser capaz de comunicar lo que encuentras ( cómo reproducir un error, escribir los pasos de un caso de prueba, explicarlo a una audiencia grande).
- **Atención a detalles, curiosidad y sentido común**  
Se requiere tener un pensamiento crítico con atención a detalles desde el punto de vista de un usuario final.
- **Ser organizado y metódico**  
Esto es clave para poder ejecutar los casos de prueba en un orden y poder encontrar la mayor cantidad de errores. Debemos seguir una metodología, todos los casos de prueba deben estar organizados de una manera lógica y secuencial ya que algunos casos de prueba requieren de datos. También se debe ser organizado con la documentación de los casos.
- **Apasionado por la tecnología**  
Tener gusto por la informática, ser curioso y creativo. Debemos ser capaces de configurarla y desconfigurarla ( ser capaces de dañarla y encontrar la mayor cantidad de errores a partir de ser curiosos ).
- **Paciencia y persistencia**  
El desarrollo de software es un proceso que requiere flexibilidad y mucha paciencia.

---

### Video 5

#### ***Responsabilidades de un Tester / QA***

Diferencias entre tester y QA. Aunque en la práctica parecen lo mismo ( para las empresas ) en la teoría un QA ( Quality Assurance Assistant ) es el encargado del aseguramiento del todo el proceso de desarrollo del proyecto ( macro ) y el tester se encarga de la ejecución de las pruebas.

- **Plan de pruebas**  
¿Qué, Cómo y Cuándo se va a probar?. Como testers somos encargados de diseñar un plan de pruebas ( depende mucho del tipo de proyecto que estemos trabajando ). Si es un proyecto grande vamos a elaborar un plan de pruebas
- **Casos de prueba**  
Basado en los requisitos o criterios de aceptación.
- **Gestionar el ambiente y los datos de prueba**  
Lugar en dónde se va a probar la app con apoyo de alguien que nos ayude a configurar la app ( DevOps Engineer ).
- **Ejecutar los casos de prueba**  
Con distintos datos pruebas para encontrar la mayor cantidad de errores posibles.
- **Realizar la documentación de las pruebas realizadas**  
Generar evidencia para reproducir un error.
- **Reportar los errores encontrados y realizar seguimiento para su corrección y re-validación**  
Generar los reportes según sea lo correcto y dar seguimiento hasta que finalice su ciclo de vida.
- **Participar en las reuniones de seguimiento diarias y todas las de SCRUM**  
Participar en las reuniones de equipo.
- **Realizar informes de calidad del producto**  
Realizar un reporte de pruebas.
- **Ayudar a resolver dudas a los *Analistas de Requisitos* o *POs***  
Resolver dudas del equipo. Somos como un punto de referencia para el resto del equipo.
- **Ayudar a los programadores a replicar los errores e investigar su solución**  
Ayudar a replicar errores e investigarlos.
- **Implementar prácticas de aseguramiento de calidad para prevenir errores en el código**  
Sugerencias de cómo implementar pruebas unitarias, pruebas a los requisitos. Implementar sugerencias sobre los criterios de aceptación.

---

### Video 6

#### ***¿Puedo trabajar como Tester sin tener una carrera en TI o relacionada con Informática o Sistemas***

> Si, tener una carrera o profesión relacionada con tecnología ayuda pero no es indispensable. Para muchas empresas hoy en día no importa que carrera tengas, importa más tus skills ( habilidades, experiencias y cómo puedes plasmarlos en una hoja de vida y demostrarlos en una entrevista ).
Se puede comenzar como un *Tester Funcional Junior* sin tener una carrera en tecnología siempre y cuando se tenga la experiencia y habilidades mencionadas antes.

---

## Section 3

### Video 7

#### **Fundamentos del proceso de desarrollo de software**

El software se construye a traves de la ingeniera del software que es un proceso multifacético que conlleva numerosos pasos previos al lanzamiento de un programa, es por esta razón que la comunidad de desarrollo de software crearon metodologías de trabajo que administren el ciclo de vida de un proyecto.

- ***Modelo de Desarrollo en Cascada***  
El SDLC ( Software Development Life Cicle ) es un marco que define los pasos involucrados en el desarrollo de software
*Propósito*  
Entregar un producto de alta calidad que cumpla con las expectativas del cliente.  
*Desventajas*  
  - No permite cambios de requisitos.
  - Solo se tiene un producto funcional al final del ciclo.
  - En ocasiones, los fallos se detectan después de la fase implementación.
  - El usuario final se integra al final del ciclo de desarrollo.

---

### Video 8

<!-- Metodologías de desarrollo ágiles -->
- ***Modelo de Desarrollo SCRUM***
Scrum es un proceso en el que se aplica de manera regular un conjunto de buenas prácticas para trabajar de manera colaborativa en equipo y obtener el mejor resultado posible de un proyecto.  
El producto se divide en pequeñas iteraciones que se llaman *Sprints*.
Un **Sprint** ( *Ciclo Iteración* ) es un periodo de tiempo dónde el equipo ( Product Owner, Scrum Master, Team ) se compromete a entregar la funcionalidad en cierto tiempo ( el tiempo del Sprint ).  
*Ventajas*  
  - Flexibilidad y adaptación a un mercado cambiante.
  - Resultados anticipados.
  - Obtención de un producto mínimo viable ( *MVP* ).
  - Feedbacks rápidos.
  - Fecha de entrega de proyecto realista.
  <!-- - Feedbacks rápidos y precisos. -->
  <!-- - Rápido aprendizaje del equipo. -->
  <!-- - Autonomía y  responsabilidad. -->

---

### Video 9

#### **Roles en Scrum**

- **Scrum Master:** Experto que ayuda al equipo a trabajar bajo el marco de scrum, es un facilitador y ayuda a resolver los impedimentos, no es un *PM* ( **P**roduct **M**anager ).
- **Product Owner:** Representa la voz del cliente o negocio dentro del equipo de desarrollo, es el encargado de indicar lo que se debe hacer y controla el flujo de trabajo ( *Backlog* ). Responde a la pregunta ¿Qué se va a hacer?
- **Team:** El *equipo de desarrollo* está compuesto por *Desarrolladores ( Dec )*, *Analistas de requisitos ( BA )*, *Testers ( QA )*, *Arquitectos*, *Diseñadores*.

---

### Video 10

#### **Eventos en Scrum**

El corazón de Scrum es un **Sprint** ( un *Sprint* es un ciclo de iteración ), que puede ser de dos a cuatro semanas ( recomendado ), y durante ese tiempo se llevan a cabo reuniones.

0. **Sprint Backlog**: Son las necesidades que requiere el product owner. Se detallan y socializan las **historias de usuario** ( requisitos del cliente, necesidades del cliente ).
1. **Planeación del Sprint**: Es la primera reunión que se realiza al inicio del Sprint, el equipo de trabajo se reúne ( *scrum team*, *product owner*, *scrum master* ) y sirve para seleccionar lo items ( elementos ) en los que se va trabajar y cómo se van a hacer. Se organizan las actividades de desarrollo y de define el objetivo del Sprint. Las actividades se anotan en el *Scrum Board*.
2. **Reunión diaria ( Daily Meeting )**: Es una reunión de 15 minutos en la que cada miembro del equipo de desarrollo da un *update* de lo que está haciendo o impedimentos que tenga.
3. **Revisión del Sprint ( Review )**: Ocurre al final del Sprint dónde el product owner y el equipo presentan a los usuarios ( stakeholders ) el incremento terminado del producto para su inspección y adaptación. El tiempo aproximado de la reunión es de 1 hora. Se hacen las pruebas de aceptación de usuario ( *UAT - User Acceptance Testing*  ).
4. **Retrospectiva ( Retrospect )**: Ocurre después de la revisión del sprint, se hace una reflexión del sprint y se discuten oportunidades de mejora para el próximo sprint. El tiempo aproximado de la reunión es de 1 hora.

Al finalizar el equipo va a entregar la funcionalidad al negocio, el negocio la va a instalar en producción y los clientes van a poder comenzar a consumir la nueva funcionalidad. El negocio va a poder obtener información del uso de la aplicación y ver si hay mejoras para el siguiente sprint. Una vez el producto esté en producción se realiza una última prueba, la *prueba de sanidad*. En la **Sanity Test** del release se verifica que el producto quedó bien.

---

## Section 4

### Video 11

#### **Los 7 principios del Software Testing**

ISTQB ( International Software Testing Qualifications Board ) - Entidad que regula el software testing a nivel mundial.
Bugs - Errores de programación.

- **Principio #1**  
Ejecutar pruebas nos muestra la presencia de defectos... Pero no puede probar que no las hay.
- **Principio #2**  
El testing exhaustivo es imposible. Probar todas las combinaciones de entrada y precondiciones no es posible a excepción de algunos casos. Lo correcto es realizar un análisis de riesgo y así priorizar y ejecutar los casos de prueba de mayor importancia.
- **Principio #3**  
La verificación de la calidad de un sistema debe empezarse lo antes posible. Las pruebas de software deben empezarse lo más temprano posible durante el ciclo de vida del proyecto. Encontrar errores en etapas tempranas del proyecto ayuda a reducir costos de tiempo :watch: y dinero :moneybag:.
- **Principio #4**  
La mayoría de defectos relevantes suelen concentrarse en un grupo muy determinado de módulos de nuestro producto. A mayor número de cambios, mayor es la probabilidad de encontrar errores.
La regla del 80/20 o principio de Pareto, el 80% de los defectos se encuentra en el 20% del sistema que se está probando.
- **Principio #5**  
Paradoja del pesticida. Cuando ejecutas los mismos casos de prueba una y otra vez y sin ningún cambio, eventualmente estos dejarán de encontrar nuevos bugs. Es necesario cambiar los casos de prueba y los datos de prueba para encontrar la mayor cantidad de bugs.
- **Principio #6**  
El testing es totalmente dependiente del contexto. Se debe adecuar las pruebas al contexto del objeto.
- **Principio #7**  
La falacia de ausencia de errores...  
Es posible que los defectos críticos de una aplicación hayan sido corregidos pero esto no asegura que el software sea exitoso.

---

### Video 12

#### **Agile Testing**

Es una práctica de pruebas de software que sigue los principios del desarrollo ágil de software. Es una forma eficiente de probar software que ofrece mejores resultados finales que los métodos de prueba tradicionales ( software en cascada por ejemplo ). Dado que el desarrollo y las pruebas se integran en este proceso, permite la detección y eliminación temprana de errores, que se traduce en menos costo de dinero y tiempo de desarrollo y también permite una alta calidad de producto ya que los errores se eliminan en la etapa inicial, cuando se está desarrollando el software.  

#### *12 Principios del desarrollo ágil de software*

1. Satisfacer al cliente
2. Cambios
3. Software funcionando
4. Trabajo conjunto
5. Individuos motivados
6. Conversación cara a cara
7. Software como medida
8. Desarrollo sostenible
9. Excelencia técnica
10. Simplicidad
11. Equipos auto-organizados
12. Intervalos regulados

---

### Video 13

#### Plan de pruebas de un proyecto de de software

- Sirve para definir la estrategia de las pruebas y guía al equipo como probar la aplicación.
- Define el *¿Qué?*, *¿Cómo?*, *¿Dónde?*, *¿Quién?*
- Depende mucho de la complejidad del proyecto, por lo general para sprints cortos y con alcance muy definido un plan de pruebas lite o ágil es más que suficiente ( El plan de pruebas de pruebas se elabora al inicio del sprint ). *Plan de pruebas ágil*.
- El plan de pruebas se ajusta dependiendo del sprint.
- Lo realiza el tester al principio del sprint en conjunto con el equipo de desarrollo.
- Debe estar al alcance de todos.

#### Plan de pruebas ágil

- ***Introducción*** -> Una descripción breve de lo el cliente requiere para el proyecto.
- ***Alcance de las pruebas*** -> Qué historias de usuario o requisitos se están probando para resolver la necesidad. Esta información la obtendremos de los Business Analyst, los analistas de negocio, porque ellos ya escribieron las necesidades del cliente y esas necesidades vienen del dueño del producto y basado en esa información vamos a definir que es lo que se va probar. ¿Qué se va a probar? pruebas funcionales ( pruebas de lo que está en los requisitos ).
- ***Fuera del alcance*** -> ¿Qué es lo que no se va a probar? ¿Qué es lo que no se va a considerar?, fuera del alcance de las pruebas. Por ejemplo: pruebas de carga, stress, concurrencia, pruebas de seguridad.
- ***Tipos de prueba / Estrategia*** -> Por ejemplo, las pruebas de exploración consisten en diseñar casos de prueba a medida que se va explorando la aplicación. ¿Cómo ejecutar las pruebas?
- ***Ambiente de la prueba*** -> Por ejemplo, en una aplicación web, la dirección de la página web o lugar dónde se prueba la aplicación. Las pruebas se hacen en ambientes controlados. Esto debe estar definido en los casos de prueba con sus direcciones.
- ***Datos de prueba*** -> Nombres de usuario, e-mail, direcciones. También deben estar en el plan para que todos los que estén probando, revisen con qué datos se están probando y qué datos están disponibles.
- ***Plan de riesgos*** -> También deben incluirse junto con la forma de mitigarlos.

---

### Video 14

#### Historias de usuario ( Necesidades )

Están escritas desde el punto de vista del cliente, generalmente tienen la siguiente estructura...

- **Como**: < Rol del usuario >.
- **Quiero**: < Objetivo >.
- **Para**: < Beneficio >.
- **Criterio de aceptación**: < Outcome >

**Suite de pruebas**: Es un conjunto de casos de pruebas basados en los criterios de aceptación relacionados a un proyecto, todo ese proyecto está definido en una Suite de pruebas y está separado por áreas funcionales. El primer caso de prueba siempre va a ser el ***Happy Path*** ( *el caso de prueba positivo* ), el caso de prueba que va a cumplir con todos los requisitos.  

#### Ejemplo de una Suite de pruebas

~~~text
| No. | Caso de prueba | Prioridad | Precondiciones | Datos de entrada | Pasos | Resultado esperado | Resultado obtenido | Estado de la Prueba |
~~~

---

### Video 15

<!-- Aquí un enlace automático -->
#### Tu turno de diseñar casos de prueba para <https://buggy.justtestit.org/>

**Objetivo**: Leer las historias de usuario definidas para el sitio Buggy Cars y a partir de este, diseñar casos de prueba positivos y negativos que nos permitan abarcar todas las funcionalidades y detectar los bugs. Con este ejercicio se pretende medir el *pensamiento lógico*, *atención a detalles*, *comprensión de las historias de usuario*, *creatividad y diseño de casos de prueba*.

1. Leer las historias de usuario definidas por el BA ( Business Analyst ) para el sitio Buggy Cars.
    - a) La clave debe tener como ***mínimo 8 caracteres***, incluyendo al menos una ***letra mayúscula***, un ***carácter especial*** y un ***número***.
2. Descargar la plantilla de casos de prueba en excel que se encuentra como recursos en este capítulo.
3. Proceder a diseñar los casos de prueba utilizando todas las técnicas aprendidas hasta el momento.
4. Ejecutar los casos de prueba y documentarlos en el mismo archivo.

<!-- Aquí un ejemplo de enlace en línea -->
Archivo editado en este [enlace](https://docs.google.com/spreadsheets/d/14vpZjqGzodbcaAxsleGzLNYzWyfKUx4v6Oa23FQRf3o/edit#gid=406087718 "Hojas de cálculo de google")

---

### Video 16

#### **¿Qué es un bug?**

Se refiere a un **error o defecto en el software** que hace que un programa no funcione correctamente. La mayoría de los bugs se originan por *errores de quienes desarrollan el código de un software o sistema*, al diseñar estos o al no ser compatibles con otros programas o hardware.

Si se reporta un bug de manera eficiente un bug la probabilidad de que se resuelva el bug es mayor. La solución de una falla dependerá de la eficiencia con que se reporte la misma. Como testers debemos asegurarnos que los bugs son reportados exitosamente.

#### **Estructura básica de un reporte de bug**

- Identificador del bug
- Titulo del error
- Reportado por
- Descripción del error
- Pasos de reproducción
- Resultado esperado
- Resultado obtenido
- Impresión de pantalla / Video ( Evidencia )
- Sistema operativo / Browser
- Severidad / Prioridad

¿Cómo reportar un bug? Se puede hacer en excel, word o si la empresa maneja algún bug tracker como ***JIRA***, ***Azure DevOps***.

---

### Video 17

Ejemplos de reportes de bug.  
Cuando ya se han realizado todos los casos de prueba podemos ejecutar las pruebas exploratorias ( libres ). Es cuando se prueba el proyecto de forma libre, son pruebas que no están en los criterios de aceptación ( historias de usuario ), si se encuentra algún bug debe reportarse.

---

### Video 18

Otros sitios para que practiques.

---

### Video 19

Encontrar todos los bugs restantes de <https://buggy.justtestit.org/>  
**Requisitos previos**: Para poder empezar esta actividad ya debes haber terminado el diseño y ejecución de los casos de prueba básicos sobre el sitio de la actividad del capítulo 17.  
**Objetivo de la actividad**: Esta actividad pretende medir varias habilidades como la *atención a los detalles*, el *pensamiento crítico*, tu *capacidad para encontrar bugs* como también la *forma como los documentas*. Todas estas son habilidades primordiales dentro del Testing.

1. En tu browser abrir el sitio objeto de pruebas [Buggy Cars](https://buggy.justtestit.org/ "Sitio de pruebas")
2. Descarga la plantilla de reporte de bugs, y procede a documentar la mayor cantidad de bugs que encontraste en tus pruebas, usando el mismo archivo siguiendo la misma estructura de la tabla.

***Nota***

- Trata de encontrar la mayor cantidad de bugs posibles desde el punto de vista de un usuario final, ***el sitio tiene 16 bugs en diferentes páginas***.
- Ejecutar pruebas en varios navegadores
- Ejecuta pruebas de visualización en varios móviles usando Google Chrome DevTools.

#### *Lista de bugs*

- bug #1 Al hacer clic en el botón de navegación **"Buggy Rating"**, el botón no ejecuta la acción
- bug #2 ordenar la lista de los autos por "Rank"
- bug #3 botones de navegación avanza a páginas inexistentes
- bug #4 error en miniatura de auto en la página 5
- bug #5 se puede ver la información de un usuario después de cerrar sesión
- bug #6 el buscador de paginas no funciona correctamente
- bug #7 cuando haces clic en el botón de navegación "siguiente" agrega un dígito más al cuadro de navegación

---

### Video 20

Reportando un bug en ***Jira Software***

---

### Video 21

#### Ciclo de vida de un bug

- Cuando el tester encuentra un bug, falla o error (en los casos de prueba o pruebas exploratorias) genera un reporte de bug con un estado de ***Nuevo***.
- Después de que es creado pasa a estado ***Activo***.
- El Tester lo asigna a un programador y cambia a estado ***Asignado***.
- EL encargado de resolver el bug puede determinar, "No es un defecto o está duplicado", o sea que el o la asignado(a) determinan si lo que se reporta no es un bug o si ya existe un ticket asignado a ese error (bug) y entonces el reporte cambia de estado a ***Rechazado***.
- O puede determinan que si es válido el reporte y proceder a corregir el error. Entonces, el reporte cambia de estado a ***Arreglado***.
- Después el reporte pasa a el estado ***Verificado*** y el Tester prueba que la solución funcione y si no funciona es reasignado al mismo programador.
- Si la solución funciona se pasa al estado ***Cerrado***, se documenta la prueba y se cierra el bug.

---

### Video 22

***Tipos de prueba***

#### **Pruebas Funcionales**

Las pruebas funcionales garantizan que las características y funcionalidades del software se comportan según lo esperado sin ningún problema, son pruebas basadas en requerimientos del software, escritas en historias de usuario.

- ***Pruebas Unitarias***
Se hacen en tiempo de desarrollo, son automatizadas por programadores y se validan los resultados esperados a nivel de código. Por ejemplo, una prueba que valida el valor de una variable. Son pruebas técnicas que se hacen a nivel de desarrollo.

- ***Smoke Test***
Se realiza después de ejecutar una build del software para asegurarnos de que ciertas funcionalidades básicas y críticas del programa funcionan correctamente. Es la prueba típica dónde vamos a verificar que la aplicación al menos si carga. es la primera prueba para verificar la estabilidad de la aplicación.

- ***Pruebas de Integración***
Este tipo de pruebas se hacen cuando el proyecto es muy grande y se tienen muchos módulos, muchas interfaces por lo que se realizan para validar que un módulo que se integra con otro módulo funciona correctamente entre ambos.

- ***Pruebas de regresión***
Consiste en probar un sistema que ha sido analizado previamente para asegurar que no se haya introducido algún tipo de defecto como resultado de cambios realizados. Se recomienda automatizarlos, también, que se hagan al final de cada sprint cuando se tenga lista una funcionalidad que va a ser lanzada a producción.

- ***Pruebas de aceptación UAT***
Son pruebas que hace el cliente o el usuario final una vez se han hecho todas las demás pruebas. También conocida como prueba **beta** o de **usuario final*, se define como la prueba del software por parte del usuario o cliente para saber si puede ser aceptado o no. El objetivo principal de esta prueba es validar que el software frente a los requisitos comerciales.

> Las 'pruebas manuales' hechas anteriormente son 'funcionales'

#### **Pruebas no funcionales**

Se enfocan en características no funcionales del sistema, por ejemplo, características como el rendimiento, estabilidad, accesibilidad, sostenibilidad, capacidad, compatibilidad.

- ***Pruebas de rendimiento ( Performance )***
Es una técnica de prueba de software no funcional que determina cómo la estabilidad, la velocidad, la escalabilidad y la capacidad de respuesta de una aplicación se mantiene baja una determinada carga de trabajo. Pruebas de carga o de estés. Son pruebas que se hacen con software especializado ( Apache JMeter, SoapUI ) que simulan carga sobre un sistema, por ejemplo una carga excesiva de usuarios ingresando información en un formulario en una página web.

- ***Pruebas de seguridad***
Se pueden definir como el conjunto de actividades que se llevan a cabo para encontrar fallas y vulnerabilidades en aplicaciones web, buscando disminuir el impacto de ataques a ellas y pérdida de información importante.Son pruebas que se hacen en ambientes controlados con software especializado que hacen testers especializados en pruebas de seguridad, pueden ser hackers o hackers éticos que por medio de técnicas sofisticadas y avanzadas encuentran fallas de seguridad.

---

## Section 5

### Video 23

***Herramientas usadas en testing***

- Capturas de pantalla / Cross Browser Tests
- Gestor de proyectos Scrum / errores
- Gestor de casos de prueba
- Automatización de pruebas / API testing

---

### Video 24

Herramientas para capturar pantalla y vídeo

---

### Video 25

Overview de JIRA, Azure DevOps y Trello.

---

### Video 26

TestRail gestor de casos prueba

---

### Video 27

Google Chrome Dev Tools

---

### Video 28

VSCode + GitHub

---

### Video 29

Cross browser y mobile testing

---

## Section 6

### Video 30

#### **Pruebas manuales**

Son ejecutadas directamente por uno o más testers, simulando las acciones del usuario final, apoyándose de las herramientas necesarias.

***Ventajas***

- Para proyectos cortos son más rápidas. Si el proyecto dura uno o dos Sprints y no se va a volver a trabajar en el mismo proyecto. No hay necesidad de invertir mucho tiempo programando casos de prueba que no se van a volver a ejecutar.
-Son más flexibles. Permite al tester la creatividad en la ejecución o combinación de casos alternativos.
- Al ser ejecutadas por un humano pueden detectar problemas o bugs no funcionales que no son detectados por un programa como lo es la usabilidad, la navegabilidad o experiencia de usuario.
- No requieren de conocimiento técnicos profundos o programación aunque sería ideal.
- Permiten probar escenarios complejos con secuencias largas de pasos en sistemas antiguos difíciles de automatizar.

***Desventajas***

- Se pueden volver una actividad repetitiva y tediosa cuando se trata de proyectos grandes. Ejemplo: Estás trabajando en un proyecto de 5 o 6 meses donde al finalizar cada Sprint debes correr las pruebas de regresión y estas pruebas son una cantidad de casos de prueba que se hacen manualmente, esto tomaría mucho tiempo y puede retrasar al equipo y eso estaría violando una de las variables de restricción.

> Las variables de la **Triple Restricción** son **Alcance, Costo y Tiempo**.

- Cuando el proyecto tiene muchos bugs, las repruebas y pruebas de regresión se vuelven muy costosas de ejecutar. Esto está relacionado con lo anterior y es que si un sistema tiene muchos bugs quiere dicer que cada vez que haya un arreglo de uno de esos bugs tenemos que volver a ejecutar la prueba.
- En proyectos grandes, la repetición de pruebas manuales pueden hacer que el QA omita defectos debido al cansancio.
- Poca reusabilidad, cada vez que se hace un cambio se debe volver a probar todo desde cero. Los cambios en el sistema ( basados en el requerimientos ) hacen que todo se vuelva a probar, se tiene que hacer todo desde cero.

#### **Pruebas automatizadas**

Son programadas por medio de scripts y programas, simulando las acciones del usuario final. Las pruebas se ejecutan automáticamente en un servidor de pruebas, laptop o un sistema de integración CI / CD.

***Ventajas***

- La ejecución de casos es rápido y eficiente.
- Brindan un mayor grado de confiabilidad y precisión.
- Tienen un mayor **ROI** ( *Return of Investment* ), en proyectos grandes ayuda a reducir costos en pruebas y detección de bugs. Si el proyecto tiene muchos Sprints y vamos a correr la misma "*n*" veces prueba en cada Sprint, vale la pena pensar automatizar esa prueba porque la vamos a correr tantas veces que vamos a tener un alto grado sobre esa inversión inicial que es diseñar la prueba ( automatizarla ), especialmente los casos que mas se corren, como las pruebas de regresión.
- Son reusables, se pueden correr una y otra vez en minutos con alto grado de cobertura. Se pueden programar para que corran en cualquier momento sin intervención humana.
- Las pruebas se pueden programar para que corran a cualquier momento sin intervención humana CI / CD.

***Desventajas***

- Automatizar las pruebas requiere una inversión de tiempo.
- Automatizar pruebas requiere de un conocimiento técnico que algunos QAs principiantes aún no tienen.
- Algunas herramientas de automatización son costosas.
- Las pruebas automáticas no proveen de un feedback de aspectos del sistema como la usabilidad.

---

### Video 31

Instalación + primeros pasos en Selenium IDE ( caso de prueba "Registrar nuevo usuario" )

---

### Video 32

Selenium IDE caso de prueba "Validación página de inicio"

---

### Video 33

Herramientas básicas de Selenium IDE

---

### Video 34

---

### Video 35

#### Automatizando suits de pruebas usando **Selenium IDE**

***Sitio de pruebas***: <http://automationpractice.com/index.php>

- Validar los elementos básicos de la página de inicio
  - Validar header de la parte superior con la imagen 70% off esté visible.
  - Validar el número telefónico de contacto de la parte superior izquierda sea 0123-456-789.
  - Validar logo de la parte superior izquierda siempre sea visible.
  - Validar caja de búsqueda de la parte superior sea visible.
  - Validar que al dar clic al botón superior derecho "**Sign in**" se abra la página de autenticación, el titulo de dicha página debe decir "*Login - My Store*".
- Automatizar la compra de un articulo de la tienda
  - Busca el siguiente artículo "Faded Short Sleeve T-shirts".
  - Validar que la imagen del artículo sea visible.
  - Validar que el precio sea **$16.51**.
  - Validar que se pueda adicionar al carrito y proceder al checkout.
  - Validar que el precio total con impuestos en el resumen del checkout sea **$18.51**.

---

### Video 36

#### **Automatización de pruebas con *Cypress* y *Javascript***

Cypress es un framework de testing automatizado moderno y todo en uno. Es rápido, fácil de usar y permite ejecutar pruebas sobre cualquier aplicación web. Cypress corre en Node.js

Cypress te permite crear pruebas automatizadas.

- End to end -> De un extremo a otro, un caso de prueba completo con muchos pasos, desde una página hasta otra probando diferentes cosas en el transcurso.
- Pruebas de integración -> pruebas de APIS, pruebas de componentes.
- Pruebas unitarias

***Ventajas***

- Cypress tiene un ejecutor de pruebas que nos permite seleccionar el browser en donde queremos ejecutar las pruebas.
- Nos permite crear fotos, snapshots, vídeos de las pruebas.
- Nos muestra los resultados en la consola.
- Podemos generar reportes en HTML.
- Tiene bastante documentación en internet.
- Es gratis

---

### Video 37

Instalación de VS Code, Node.JS, NPM y Cypress

---

### Video 38

Primeros pasos con Cypress

---

### Video 39

Pruebas End to End transferencias

---

### Video 40

Hooks, fixtures y ejecutar pruebas por CLI modo headless con parámetros

---

### Video 41

Cypress es un herramienta de automatización de pruebas de software, especialmente para páginas web, utiliza javascript, node.js

---

### Video 42

Descargar el código Cypress

---

### Video 43

#### Actividad de automatización con Cypress

***Sitio de pruebas***: <http://automationpractice.com/index.php>

- **Suit de casos de pruebas para que se valide los elementos básicos de la página de inicio**

  1. Validar que el logo de la parte superior izquierda siempre sea visible.
  2. Validar que la caja de búsqueda de la parte superior sea visible.
  3. Validar que el header superior con la imagen "70% off" esté visible.
  4. Validar que número telefónico de contacto de la parte superior izquierda sea 0123-456-789.
  5. Validar que al dar clic al botón superior derecho "*Sign in*" se abra la página de autenticación, el título de dicha página debe decir "**Login - My Store**".

- **Automatiza una compra de un artículo de la tienda**
  1. Busca el siguiente artículo "Faded Short Sleeve T-shirts".
  2. Validar que la imagen del artículo sea visible.
  3. Validar que el precio sea **$16.51**.
  4. Validar que se pueda adicionar al carrito y proceder al checkout.
  5. Validar que el precio total con impuestos en el resumen del checkout sea **$18.51**.

---

## Section 7

### Video 44

#### ¿**Qué es una API**?

Una **API** ( *Application programing interface* ) es un conjunto de procedimientos y funciones creados para permitir la comunicación entre 2 aplicaciones, o una aplicación con una base de datos u otro sistema, también son usadas comúnmente por páginas web para reutilizar servicios que ya han sido creados por grandes compañías como por ejemplo Google, Facebook, PayPal, Twitter, etc.

Las APIS, tienen una URL ( recurso ), método ( GET, POST, DELETE ) y un código de estado ( 200, 400 )

---

### Video 45

<!-- Aquí un enlace como referencia -->
Ejemplo de una API en un sitio real [BuggyCars][referencia]

[referencia]: https://buggy.justtestit.org/

---

### Video 46

#### **API Testing**

Lo que hace es validar y verificar que las funcionalidades responden correctamente, por lo que se considera un tipo de prueba a bajo nivel, es decir, que no interactuá directamente con la interfaz de usuario. Es indispensable hacer pruebas en APIS para tener mayor cobertura en las pruebas y aportar mayor calidad al producto final.

***Beneficios de API testing***

- No es necesario contar con el producto totalmente terminado para comenzar a probar, basta con tener conexión a las APIS para ir probando sus funcionalidades.
- Mayor velocidad de ejecución.
- Reducción de errores.

#### **Pirámide de pruebas**

Es una guía sobre qué tipos y cuántos de cada tipo de prueba realizar. La pirámide de automatización de pruebas ayuda a crear pruebas más eficientes y ha dado como resultado software más confiable.

Es una gran metáfora visual que describe diferentes capas de prueba y cuántas pruebas se deben realizar en cada capa.

![Pirámide de pruebas](https://www.parasoft.com/wp-content/uploads/2021/04/Simple_Testing_Pyramid_20210402-1-300x276.png, "Pirámide de pruebas")

**Pruebas Unitarias**: Están en la parte inferior y representan las pruebas más granulares, de las cuales debería tener muchas.

**Pruebas de capa de integración o de servicio**: Es donde comienza a probar cómo interactúan sus componentes de software entre sí, ya sean integraciones internas o externas.

**Pruebas de extremo a extremo (E2E)**: Es el más complejo y prueba el software en su conjunto para asegurarse de que funciona como se espera de principio a fin.

***Beneficios***

- Ahorro de tiempo y costes
- Mejor precisión eliminando errores humanos
- Capacidad para repetir, reutilizar y escalar pruebas según sus necesidades de software

---

### Video 47

#### **Ejemplos de pruebas de APIS**

1. *Pruebas de funcionalidad*  
Verifican los requisitos operativos del producto. Estas funciones utilizan escenarios particulares para asegurarse que la API funciona según los parámetros previstos. Por ejemplo, probar que la API respondió con un estado **200** o no.
2. *Pruebas de carga*  
Comprueban si el API tiene la capacidad de manejar una cierta cantidad de carga. Revisa  cómo se comporta una API particular bajo cargas más altas de las que debía afrontar.
3. *Pruebas de seguridad*  
Incluyen las necesidades de seguridad de la API. Contiene permisos, autenticaciones y controles de acceso.

---

### Video 48

Haciendo pruebas de APIS en **Postman** en el sitio *Buggy Cars Rating*

---

### Video 49

#### **Ejercicio API testing**

**Objetivo**: Usando *Postman*, crear una suite de pruebas automáticas para las siguientes APIS

- **API Usuarios** <https://jsonplaceholder.typicode.com/users>
  1. Validar que la API devuelva un estado 200
  2. Validar que la API devuelva en la respuesta los campos *username*, *address*, *city*
  3. Validar que la API responda en menos de 800 milisegundos
- **API Comentarios** <https://jsonplaceholder.typicode.com/comments>
  1. Validar que la API devuelva un estado 200
  2. Validar que la API devuelva en la respuesta los campos *name*, *email*, *body*
  3. Validar que la API responda en menos de 900 milisegundos
- **API de fotos** <https://jsonplaceholder.typicode.com/photos>
  1. Validar que la API devuelva un estado 200
  2. Validar que la API devuelva en la respuesta los campos *albumId*, *title*, *url*
  3. Validar que la API responda en menos de 800 milisegundos

---

### Video 50

Descargar la solución del ejercicio anterior

---

## Section 8

### Video 51

#### ¿**Cómo encontrar trabajo en Testing**?

1. ¡*Crea una hoja de vida que impacte al empleador*! Si tienes repositorios en GitHub con proyectos trabajados seria ideal.
2. **Crea tu perfil de LinkedIn**
    1. Incluye palabras clave y herramientas de testing en tu perfil.
    2. En cada experiencia que tengas, debes poner tus funciones básicas, tecnologías trabajadas y si tienes algún reconocimiento.
    3. Incluye todos los cursos relevantes a software testing.
    4. Pídele a tus contactos que te validen conocimientos.
    5. Pídele a tus contactos que te den recomendaciones y que describan proyectos de IT en los que hayas participado.
    6. Genera valor en LinkedIn, escribe artículos sobre Testing para ganar visibilidad y reputación en la materia.
    7. Sigue a las empresas de Software y Testing de tu ciudad en LinkedIn.
    8. Adiciona a otros referentes de Testing en tu área como también reclutadores.
    9. Escribe un post en tu perfil diciéndole a tu red que estás buscando trabajo como Tester.

Es muy importante dedicarle tiempo a la *Hoja de Vida* o *CV*

---

### Video 52

Creando perfil de LinkedIn

---

### Video 53

Únete a grupos en Facebook, LinkedIn sobre Testing de Software o QA, también puedes usar meetUp

---

### Video 54

#### ¿***Cómo ganar experiencia cuando eres principiante como QA freelancer***?

- Haciendo Freelance en páginas como [**UTest**](https://www.utest.com/), [**UpWork**](https://www.upwork.com/), [**fiverr**](https://es.fiverr.com/?utm_source=google&utm_medium=cpc-brand&utm_campaign=g_mx-es_brand_desktop_exact&utm_term=one-fiverr_%28exact%29&utm_content=AdID%5E479148884616%5EKeyword%5Efiverr%5EPlacement%5E%5EDevice%5Ec&caid=11599025189&agid=114008777758&ad_id=479148884616&kw=fiverr&lpcat=br_general&show_join=trueu_sou%3Dgoogle&u_med=cpc-brand&u_cam=g_mx-es_brand_desktop_exact&u_ter&u_con=AdID%5E479148884616%5EKeyword%5Efiverr%5EPlacement%5E%5EDevice%5Ec&gclid=CjwKCAiAxJSPBhAoEiwAeO_fPw681vPfdlrXMFprbdY0JrI5gdlyr-4TorYnkut6jTJnfvtHRwXrjxoC0S0QAvD_BwE) o [**freelancer**](https://www.freelancer.com/)
- Ser voluntario en Startups o proyectos que apenas arrancan en internet. Por ejemplo, escribir en Facebook o LinkedIn que apenas están comenzando su camino como testers o QAs y que quieren trabajar como voluntarios y que al final puedan certificarlos.
- Probar páginas o proyectos existentes, crear casos de prueba, ejecutarlos, automatizarlos y subirlos a un repositorio. Si encuentras bugs, reportarlos a la empresa te sirve para demostrar experiencia.

---

### Video 55

Salarios de Testing por países

---
