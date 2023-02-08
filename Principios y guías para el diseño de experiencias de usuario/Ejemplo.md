---
order: 7
---

# Ejemplo de Design Thinking

Consideremos el siguiente escenario: el tutor debe conocer el estatus académico de sus estudiantes para efectos de reportes, reinscripciones, riesgos de deserción o de no finalizar la ingeniería. La información se encuentra en el SIE pero el sistema es bastante confuso para "leer" esta información de forma rápida. Por otra parte, se tiene un sistema institucional de tutoría académica en la cuál debería estar también presente dicha información.

## Empatía

En este caso por entrevista y conversación con los tutores se encuentran las siguientes situaciones:

- Entrar al SIE es engorroso.
- El SIE no tiene un apartado que literalmente me diga dicha información. Debo analizar el KARDEX del alumno para determinar esto.
- Leer el KARDEX es también algo confuso pues es "puro texto".
- Algunos códigos no son comprensibles de forma inmediata.
- No quiero "perder tiempo" revisando esto, tengo otras actividades que hacer.

Podemos aplicar algunas otras técnicas para ampliar el tema pero tenemos un punto de partida aquí. Recordemos que en esta metodología podemos volver sobre nuestros pasos según convenga.

## Definición

Utilizando la técnica de las 4 W's, debemos responder las siguientes cuestiones:

- Who is experiencing the problem? *El tutor de grupo.*
- What is the problem? _No tiene una forma rápida y simple de ver el "estatus académico" del estudiante_.
- Where does the problem present itself? _En las reinscripciones y ante las solicitudes "urgentes" de esta información_ 
- Why does it matter? _porque esto es una acción continua a lo largo del proceso tutoral_

El enunciado resultante de responder estas cuestiones podría ser:

> El tutor de grupo requiere un mecanismo de acceso y lectura rápida para ver el estatus académico de un estudiante que facilite los procesos de reinscripción y generación de reportes urgentes durante todo el tiempo que dure su asignación.

Este enunciado del problema también puede ser modificado según avance el proyecto pero ya nos puede servir de guía.

## Ideación

Esta etapa es donde nos ponemos creativos para proponer soluciones que se reflejarán en la siguiente etapa de prototipado. 

Por __analogía__ podemos pensar en los perfiles rápidos que se ven de los jugadores de un equipo deportivo durante una transmisión en TV. Estos perfiles permiten ver de un "vistazo" lo relevante de un jugador. Esta podría ser un diseño inicial.

Utilizando __Challenging Assumptions__ algunas ideas preconcebidas a considerar serían:
- La mayoría de los alumnos tienen un estatus ideal.
- Los primeros dos semestres no tienen conflictos aún cuando estén reprobados.
- Los primeros dos semestres solo presentan _riesgo de deserción_.
- Los alumnos de los semestres séptimo, octavo y noveno técnicamente no tienen problemas para finalizar.
- Solo revisamos esta información al inicio de semestre para las reinscripciones y en contadas peticiones de información puntual de un alumno.

Con __reverse thinking__ pensaríamos lo opuesto a lo solicitado para visualizar a través de la exageración lo que podría funcionar a favor. Por ejemplo, algunas ideas en reversa:

- Debería mostrar toda la información detallada, calificaciones, reportes de asistencia, promedios por asignatura, semestrales y anuales.
- la información debe mostrarse en un reporte extenso de al menos 5 páginas en PDF.
- debe elegirse alumno por alumno, indicarse el semestre por semestre, asignatura por asignatura para ver la información.
- no necesito ver la cara del alumno, ni siquiera conocerlo, el puro dato académico es suficiente.
- el reporte solo puede verse en el navegador. Para tenerlo offline debo usar un screenshoot.

La técnica de __worst possible idea__ es muy parecida a la anterior. En esta la idea no tiene que estar relacionada con un criterio previo que estámos viendo "en reversa". Aquí podríamos considerar:

>  Para obtener el reporte debemos solicitarlo por escrito, mandarlo a la coordinación de tutoría, pedir una confirmación en control escolar y esperar cinco días hábiles para obtener el permiso para buscar manualmente la información dentro del sistema viendo las páginas impresas.

Hay más técnicas disponibles pero con esto hay un punto de partida para la siguiente fase.

En este punto las ideas que posiblemente incluya en el prototipo serían las siguientes:

- Los alumnos con estatus ideal solo se indican en un listado aparte, eso significa que no hay necesidad de revisar su historial, ya que no deben nada.
- Indicar con algún elemento visual el _riesgo de deserción_ principalmente en los primeros semestres.
- Una opción explícita en la plataforma para acceder a este reporte.
- Una opción que descarga el reporte completo de los tutorados para no revisar uno por uno.
- Una vista de resumen para responder "rápidamente" a la pregunta de quíenes son algún tipo de riesgo.
- Mostrar datos de contacto para "reconocer" al alumno.
- Ver el kardex en un formato "gráfico" que facilite el reconocimiento del estatus de aprobación del alumno.

## Prototipado

Consiste en generar propuestas tangibles que ilustren las ideas anteriores. Hay prototipos de distintos niveles de complejidad, funcionalidad, estética e interacción. En una etapa temprana del proyecto el __paper prototyping__ es suficiente para visualizar la propuesta. 

Los primeros bocetos pueden ser para generar discusión sobre algunos elementos a incluir aunque se recomienda que sean del proceso completo para comprender mejor la dinámica que seguirá el usuario.

Algunos bocetos posibles:

![Vista resumen del estatus general de grupo](http://drive.google.com/uc?export=view&id=1T2LaKGtxWGClsG-tOpAk74x0AJs1slmh)

![Vista del kardex de un alumno en particular](http://drive.google.com/uc?export=view&id=1TF28xi4pDp-ai4vT4j-Vn1So22YmjtZx)

![Vista ampliada de una asignatura del kardex](http://drive.google.com/uc?export=view&id=1TGp1kI076-Oz1HUcsrobIoTNl64IUcIa)

## Pruebas

Por último, las pruebas, que nos darán retroalimentación por parte de lo usuarios para comprender que puntos débiles tiene nuestra solución actual. A partir de aquí, repetimos todo el proceso del Design Thinking.