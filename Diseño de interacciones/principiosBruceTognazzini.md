# Principios de diseño de interacción de Bruce Tognazzini

Los siguientes principios son fundamentales para el diseño e implementación de interfaces gráficas efectivas, bien se trate de interfaces GUI de escritorio o de la web.

- Muchas de las aplicaciones web reflejan una falta de entendimiento de muchos de los siguientes principios. Estos principios no cambian aunque se trate de una aplicación web; es más, aplicar estos principios se vuelve más importante.

- Las interfaces efectivas son visualmente comprensibles y permiten errores por parte del usuario, dándole una sensación de control. Los usuarios ven rápidamente el alcance de las opciones y comprenden como alcanzar sus metas y realizar su trabajo.

- Las interfaces efectivas ocultan al usuario el funcionamiento interno del sistema. El trabajo se guarda continuamente y con la opción de deshacer en todo momento cualquier paso que se haya dado.

- Las aplicaciones y servicios efectivos realizan el máximo trabajo requiriendo la mínima información del usuario.

## Anticipación

Las aplicaciones deberían intentar anticiparse a las necesidades y deseos del usuario. No esperes que el usuario busque o recuerde información o herramientas. Muestra al usuario toda la información y herramientas necesarias para cada etapa en su trabajo.

## Autonomía

El ordenador, la interfaz y el entorno de la tarea pertenecen al usuario, pero esto no significa que abandonemos todas las reglas.

Dale al usuario algo de "cancha". Los usuarios aprenden rápido y ganan confianza cuando se sienten que tienen el control del sistema.

Pese a lo que pueda parecer, sin fronteras o restricciones el usuario no se siente libre (Yallum, 1980); es como un niño pequeño que llora cuando se le mantiene muy atado o se le deja en un edificio grande y vacío. Los adultos también se sienten más cómodos en un entorno ni muy restrictivo ni demasiado grande, un entorno explorable pero no peligroso.

- Mantén informado al usuario del estado del sistema.

	No existe autonomía en ausencia de control; y el control no se puede tener sin información suficiente. Comunicar el estado es fundamental para que el usuario responda apropiadamente con la información disponible.

	!!!
	Ejemplo: los trabajadores sin información del estado del sistema, tienden a mantenerse bajo presión durante cortos periodos de tiempo hasta que el trabajo se termina. Un estrés y fatiga innecesarios por lo que cuando venga la siguiente carga de trabajo, puede que los trabajadores no estén en las mejores condiciones físicas y mentales.
	!!!

- Mantén la información de estado fácilmente visible y actualizada.

	Los usuarios no tienen que buscar la información de estado. De un vistazo deberían ser capaces de hacerse una idea aproximada del estado del sistema. La información de estado pude ser bastante sutil: el icono de la bandeja de entrada puede mostrarse vacía, medio llena o hasta los topes, por ejemplo. Sin embargo, no es conveniente abusar: el Macintosh utilizó durante años un icono de la papelera que parecía que iba a estallar en cualquier momento, aunque sólo tuviese un documento. Los usuarios adquirieron la costumbre de vaciar la papelera apenas contuviese un documento, convirtieron un proceso de un paso en uno de dos (primero llevamos el documento a la papelera, luego lo vaciamos). Esto tuvo el efecto negativo de reducir una de las funciones básicas de la papelera: la posibilidad de deshacer la acción.

	!!!
	Otro ejemplo posible de información de estado sería el de un una caja de búsquedas que cambiase de color para indicar si la búsqueda está todavía en marcha o si ya ha terminado, con demasiados resultados, con muy pocos o justos con lo necesario.
	!!!


## Daltonismo

- Si utilizas el color para transmitir información debes utilizar otros elementos complementarios para la gente con daltonismo.

- Aproximadamente __un 10% de los hombres adultos sufren daltonismo__.

- Las pistas secundarias pueden consistir en distintos tonos de gris, gráficos complementarios o etiquetas de texto.

## Consistencia

Los siguientes principios, vistos en su conjunto, dan al diseñador de interacción mucho margen para la evolución de un producto sin perjudicar los aspectos más importantes para el usuario.

__Niveles de consistencia__: mantener una consistencia estricta depende del caso. En la siguiente lista aparecen los elementos de la interfaz ordenados por su necesidad de consistencia, de mayor a menor. Mucha gente asume que el orden de los cinco primeros elementos es justo el contrario, dando lugar a aplicaciones que se parecen pero que se comportan de forma impredecible y totalmente distinta.

- Interpretación del comportamiento del usuario. Ejemplo: los atajos de teclado deben funcionar siempre igual.
- Estructuras invisibles.
- Estructuras visibles pequeñas.
- El aspecto general de una aplicación o servicio (presentación, elementos de diseño).
- Una suite de productos.
- Consistencia interna.
- Consistencia con la plataforma.		

Las estructuras invisibles se refieren a objetos como al botón izquierdo de Word, que tiene toda clase de propiedades y comportamientos, si es que alguna vez los descubres. A veces aparece y otras no, depende de tu versión de Windows; y si no aparece, nunca estarás seguro de si está o no, dado que es invisible. Por eso es tan importante la consistencia en los objetos invisibles.

Otros objetos en la interfaz se consideran visibles, pero muchas veces no parecen controles: es posible que el usuario nunca descubra que se pueden interactuar con ellos. Su significado, si decides utilizarlos, debería ser muy claro. "Por ejemplo, podemos hacer clic y arrastrar en una esquina de un ventana activa para cambiar su tamaño" pero no "a veces podemos hacer clic y arrastrar pero otras veces no".

Las pequeñas estructuras visibles se refiere a iconos, flechas de desplazamiento, etc. Es necesario mantener su consistencia si no queremos que la gente se pase el día averiguando cómo se hace qué con estos objetos. Su posición en pantalla es ligeramente menos importante. Si tiene sentido estandarizar la posición, hazlo.

_Inconsistencia._ Es tan importante ser visualmente inconsistente con los objetos que se comportan de forma distinta, como ser consistente con los que se comportan de igual manera.

_Evita la uniformidad._ Haz que los objetos que se comportan distinto parezcan distintos.

_La consistencia más importante es aquella que espera el usuario_. La única manera de comprobar las expectativas del usuario es hacer pruebas con ellos.

## Valores por defecto

Los valores por defecto deberían ser poder descartados con facilidad y rapidez. Los campos de texto con valores por defecto deben aparecer seleccionados, para que el usuario sólo tenga que teclear y no seleccionar todo, borrar y escribir.

Los valores por defecto deben tener sentido.

No uses la palabra "por defecto" en una aplicación o servicio. Utiliza "estándar", "Usar valores habituales", "Restablecer valores iniciales" o términos más específicos que describan lo que sucederá.

## Eficacia del usuario

_Busca la productividad del usuario, no del ordenador_

La gente cuesta mucho más dinero que los ordenadores, y aunque parezca que aumentando la productividad de la máquina aumentamos la del humano, lo habitual suele ser lo contrario. Cuando juzgues la eficacia de un sistema, vete más allá de la simple eficacia de la máquina.

Por ejemplo ¿qué lleva menos tiempo, calentar agua en un microondas durante un minuto y diez segundos o durante un minuto y once segundos?

Desde el punto de vista del microondas, la primera opción es la respuesta obvia. Pero desde el punto de vista del usuario es más rápida la segunda: sólo tiene que pulsar tres veces la tecla con el 1; de la otra forma tiene que cambiar de tecla, pulsando un cero, que suele quedar al otro lado del teclado. ¡El agua se calienta antes si la cocinamos un segundo más!

El usuario que decide repetir dígitos en el microoondas tiene que tomar menos decisiones. Dejan de decidir si las lentejas tiene que calentarse durante 2 minutos o 2 minutos 20 segundos. Hacen una estimación rápida y acaban con un resultado satisfactorio sin tanta decisión, incrementando la eficacia humana.

_Mantén ocupado al usuario_

El gasto más alto en un negocio es el trabajo humano. Cada vez que el usuario tiene que esperar la respuesta del sistema, es dinero perdido.

Para maximizar la eficacia de un negocio u organización debes maximizar la eficacia de todos y no sólo de un grupo

Las grandes organizaciones tienden a estar segmentadas, con cada grupo mirando por sus intereses, a veces en detrimento de la organización.

Los saltos cualitativos en eficacia se encuentran en la arquitectura del sistema, no en su superficie, en el diseño visual de la interfaz.

Esta es la razón por la que es tan importante que todo el mundo involucrado en un proyecto de software aprecie la importancia de hacer de la productividad del usuario el objetivo principal y entender la diferencia entre diseñar un sistema eficaz o potenciar la productividad del usuario. Esto implica que es fundamental la colaboración, comunicación y complicidad entre ingenieros y diseñadores de interacción si se quiere conseguir este objetivo.

Escribe mensajes de ayuda concisos y que ayuden a resolver el problema: un buen texto ayuda mucho en comprensión y eficacia.

Menús y etiquetas de botones deben comenzar con la palabra más importante.

!!!
Ejemplo de un procesador de texto ficticio:

Mal:

- Insertar salto de página
- Añadir nota al pie de página
- Actualizar índice

Bien:

- insertar:
	- Salto de página
	- Nota al pie de página
	- Índice

Este ejemplo puede parecer contradictorio. El primero ofrece información más precisa: uno no inserta un índice si ya existe uno, o no inserta una nota a pie de página. Aún así, en el segundo ejemplo será mucho más efectivo. La razón es que la información extra del primer ejemplo no compensa la rapidez con que se escanea las palabras más importantes del segundo.
!!!

## Interfaces explorables

Dale al usuario caminos bien señalizados; luego deja que se metan monte a través.
Imita la seguridad, suavidad y consistencia del medio natural. No encierres al usuario en un único camino, pero ofrécele la ruta de menos resistencia. Esto facilita a los nuevos usuarios o a aquellos que sólo quieren hacer acabar la tarea, hacerlo rápidamente y sin esfuerzo; pero también hay que dejar posibilidades abiertas a aquellos que quieran explorar.

A veces es necesario ofrecer caminos bien profundos y marcados.
Una interaz para una tarea poco habitual y desconocida tiene que ser mucho más directa que las interfaces para usuarios habituales.

Da a los usuarios nociones estables para saber como llegar al inicio
Los elementos visuales estables no sólo ayudan a navegar más rápido, si no que también actúan como una referencia necesaria para sentirse seguro.

Haz que las acciones sean reversibles
La gente explora. A veces quieren saber que pasaría si hiciesen una acción potencialmente peligrosa; otras veces lo hacen por accidente.

Si las acciones son reversibles, los usuarios pueden experimentar o equivocarse sin problemas.

Siempre permite el "deshacer"
Si no lo haces, tendrás que recurrir a los inevitables cuadros de diálogo "¿Estás realmente, pero realmente seguro de que quieres hacer esto?". Esto ralentiza el trabajo de los usuarios.

Sin estos cuadros de diálogo, la gente se ralentiza incluso más. Un estudio de hace unos años demostró que la gente trabajando en un entorno peligroso no comete más errores que en un entorno cómodo y que permita errores, pero si que disminuyen mucho el ritmo para evitar errores.

Siempre deja una salida abierta
Los usuarios nunca deben sentirse atrapados. Siempre hay que tener una salida clara.

De todas formas, haz que sea fácil quedarse.
Al principio era difícil salir de los programas, pero con la aparición de la web ahora tenemos software en el que es difícil quedarse.

Los navegadores están abarrotados de menús con elementos que poco tienen que ver con nuestro trabajo. Por ejemplo, sería muy difícil diseñar un procesador de texto con el menú de Photoshop.

Tener muchas opciones que llevan directamente a la destrucción del trabajo del usuario junto con algunas que también lo hacen un poco más fácil es una interfaz.

Si trabajas con transacciones delicadas, inhabilita la barra de menús y ofrece una forma clara de salir de ella.

### Ley de Fitt
El tiempo necesario para alcanzar un objeto es función de la distancia y del tamaño del objeto.

Aunque a primera vista pueda parecer obvio, es uno de los principios a los que menos caso se le hace. Como ejemplo, esta ley nos dice que los menús del Mac son aproximadamente 5 veces más rápidos de accionar que los de Windows, como así resulta. También nos dice las zonas de la pantalla más fácilmente accesibles son las cuatro esquinas, y siguen estando infrautilizadas por la mayoría de diseñadores.

Utiliza objetos grandes para las funciones importantes.

Utiliza las esquinas y bordes de la pantalla. Una lista de iconos en los que hacer clic que cuelguen de los bordes será mucho más efectiva que una paleta con una doble fila de iconos separados cuidadosamente por borde de píxeles no "clicables".

## Objetos humanos

- Los objetos humanos de la interfaz se pueden ver, escuchar, tocar o percibir de otra manera.
- Los objetos humanos visibles de la interfaz son bastante familiares. Aque- los que utilizan otros sentidos lo son menos.
- Los objetos humanos de la interfaz se comportan de manera estándar.
- Los objetos humanos de la interfaz deben ser comprensibles, consistentes y estables.

## Reducción de latencia

Cuando sea posible, utiliza el multihilo para dejar la latencia en un segundo plano.

Reduzca la percepción de latencia con:

- Comunica el clic de los botones mediante un feedback visual en los primeros 50 milisegundos.
- Muestra un reloj de arena para cualquier acción que dure entre 1/2 y 2 segundos. Que esté animado, para que el usuario sepa que el sistema sigue trabajando.
- Muestra un mensaje comunicando la duración estimada para cualquier proceso que pueda durar más de 2 segundos.
- Comunica el tamaño y el progreso con un barra de estado.
- Muestra mensajes de textos agradables y procura mantener entretenido al usuario mientras espera a que el ordenador termine.
- Indica con pitidos e indicaciones visuales muy claras cuando el usuario puede volver al trabajo con el sistema.
- Indentifica los múltiples clics en un mismo objeto.
- Haz que vaya más rápido. Elimina de la aplicación cualquier cosa que no esté ayudando.

## Aprendizaje

Lo ideal sería que no hubiese periodo de aprendizaje: los usuarios se sentarían delante del sistema por primera vez y sabrían cómo utilizarlo. Esto, sin embargo, nunca pasa.

Limita las limitaciones

La usabilidad y la facilidad de uso no son mutuamente excluyentes. Primero decide cuál es la más importante y luego aborda ambas con decisión. Es un mito que la facilidad de uso se consiga a costa de la facilidad de aprendizaje.

## Uso de metáforas

Escoge aquellas metáforas que permitan al usuario comprender los detalles del modelo conceptual.
Las buenas metáforas son historias que crean imágenes mentales.

Dale vida a las metáforas apoyándote en su percepción -vista, sonido, tacto, kinestesia- y en sus recuerdos.

Las metáforas evocan lo familiar, pero generalmente con un nuevo punto de vista. Ejemplo, en Windows 95 existe un objeto que se llama Mi Maletín. Sirve para llevarse consigo todos los archivos que se coloquen en el. Sin embargo, no actúa como transportador si no como sincronizador.

Protege el trabajo del usuario

Asegúrate de que el usuario nunca pierde su trabajo como resultado de un error suyo, los problemas de internet u otro tipo de problemas inevitables, como un apagón.

## Legibilidad

Utiliza texto con alto contraste. Procura utilizar negro sobre blanco o amarillo pálido. Evita fondos grises cuando haya texto.

Utiliza tamaños de letra que se lean bien en los monitores más comunes. Da mayor importancia a los datos e información que quieres presentar, más que a instrucciones y etiquetas.

Ten en cuenta a los mayores, cuya visión suele ser peor que la de los jóvenes.

## Guardar el estado

Debido a que la web utiliza un protocolo sin estado, nosotros debemos guardarlo en su lugar.

Probablemente necesitemos saber:

- Si es la primera vez que un usuario utiliza el sistema.
- Dónde está el usuario.
- A dónde quiere ir el usuario.
- En dónde ha estado el usuario en su sesión.
- Dónde abandonó el usuario la última sesión.

Además de saber en dónde han estado, podemos aprovechar saber qué han hecho.

La información de estado debe almacenarse en una cookie durante la sesión en el ordenador cliente. Luego se almacena en un servidor.

Los usuarios deberían ser capaces de desconectar, volver a conectarse desde cualquier otro sitio y seguir con su trabajo en donde lo dejaron.

## Navegación Visible

Evita la navegación invisible

La mayoría de los usuarios no pueden mantener mapas mentales complejos. Si tienen que hacerlo, se cansarán o se perderán.

La web es, de hecho, un espacio de navegación invisible. Nunca puedes ver del vastísimo panorama entre páginas. Una vez que el usuario llega a tu página, debemos procurar reducir la navegación al máximo y ofrecer la mínima imprescindible de forma clara y natural. Procura que parezca que el usuario está siempre en el mismo sitio, con el trabajo apareciéndosele a medida que avanza. Esto, además de evitar el uso de mapas y herramientas para la navegación, da una sensación de seguridad y control.

Lo mismo que con la web es no guardar el estado, nuestro trabajo no es aceptar a ciegas lo que dictan los arquitectos, si no añadir una capa que proteja al usuario y haga su navegación más cómoda. Que la navegación en la web sea invisible es un reto, no una característica.

Fuente: http://galinus.com/es/articulos/principios-diseno-de-interaccion.html