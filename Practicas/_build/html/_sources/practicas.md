# Prácticas SW-KG
Prácticas de la asignatura *"Web Semántica y Enlazado de Datos"*, asignatura optativa del *"Máster Universitario en Investigación en Inteligencia Artificial"* de la UNED.


## Líneas de trabajo
Se consideran tres líneas de trabajo: 
1. Recopilación, administración y explotación de grafos RDF/RDFS.
2. Declaración y uso de ontologías OWL.
3. Recopilación, administración y explotación de grafos de conocimiento.


Configuraciones de trabajo

Consultas externas

Ontologías OWL
Protégé

KG


Configuración
Datos de entrada
Ejecución
Entrega



## Contexto

````{dropdown} Asignatura de 1er curso
*Lógica proposicional* es el tema inicial de la asignatura *'Lógica y Estructuras Discretas'*: 
+ asignatura de primer curso y primer cuatrimestre 
+ común al Grado en Ingeniería Informática y al Grado en Ingeniería en Tecnologías de la Información de la UNED

Estos apuntes se ajustan en temario y en registro expositivo a esta asignatura.
````

````{dropdown} No incluye automatización de sistemas lógicos
En cuanto al temario, en esta asignatura se presentan dos sistemas lógicos: Lógica de Proposiciones y Lógica de Predicados. 

>El conocimiento de ambos sistemas lógicos permite al estudiante interpretar mejor el lenguaje matemático en que se expresan resultados de otras asignaturas así como mejorar sus propios patrones de razonamiento.

Otra línea de aplicación distinta, en cursos superiores, consistirá en la automatización de sistemas lógicos, para que sean estos agentes los que ejecuten razonamientos. No se incluyen en esta asignatura secciones (como resolución, etc) más enfocadas a esa automatización de agentes inteligentes.
````

## Avance de secciones

````{admonition} [1] El lenguaje proposicional: sintaxis y semántica
:class: dropdown, note
La Lógica Proposicional es un sistema lógico con un lenguaje formal preciso; es decir, a partir de símbolos se forman expresiones (fórmulas) con un significado sin ambigüedades.

Ese significado conducirá al reconocimiento de cada expresión como verdadera o falsa respecto a cada una de las perspectivas (interpretaciones) desde las que se puede evaluar.

Los problemas de nuestro día a día, en sus términos y con sus preguntas, se pueden acabar representando formalmente sobre este sistema. El objetivo básico de esta representación será captar los patrones de razonamiento usados en la discusión sobre ese problema y comprobar si son correctos.
````

````{admonition} [2] Cuestiones semánticas sobre fórmulas proposicionales. Su interrelación.
:class: dropdown, note
La rigidez del formalismo permitirá detectar cuándo, p. ej., varias expresiones no pueden ser verdad a la vez desde una cierta perspectiva (interpretación). O detectar cuándo una expresión es consecuencia de otras, en todo caso, de forma inevitable desde cualquier perspectiva. O cuando dos expresiones distintas en realidad quieren decir lo mismo: tienen el mismo significado desde cualquier interpretación posible.

Estas preguntas semánticas resultarán interrelacionadas, de forma tal que la respuesta a una de ellas puede indicar cuál será la respuesta a otra de estas cuestiones.

````

````{admonition} [3] Cálculos que garantizan propiedades semánticas. Inferencias.
:class: dropdown, note
Los cálculos del lenguaje operan sobre fórmulas y producen fórmulas de manera mecánica, como secuencia de pasos permitidos en ese cálculo en concreto. No se necesita consultar en ningún momento el significado de las expresiones para ejecutar la siguiente operación.

Pero en el diseño teórico de estos cálculos sí se ha tenido en cuenta el significado de cada una de las fórmulas que se van produciendo. Así, hay cálculos que garantizan que todo lo que se produce son expresiones que 'quieren decir lo mismo', que tienen el mismo significado entre sí. Otros cálculos garantizan que la fórmula producida tras unos pasos siempre es consecuencia de las fórmulas de partida, y eso es tanto como decir que estos cálculos permiten ir desarrollando razonamientos correctos.
````

## Usos y limitaciones

````{dropdown} Usos: verificación de sistemas, esquemas de razonamiento. Limitaciones.

El uso práctico de estos sistemas requiere:
+ representar o relacionar 'hacia abajo', del problema práctico al lenguaje formal, los elementos y las preguntas del problema en términos de expresiones y cuestiones formales en el lenguaje
+ operar sobre las fórmulas para obtener otras fórmulas resultantes o la respuesta 'si' o 'no' a una cuestión formal
+ interpretar 'hacia arriba' los resultados formales en términos del problema real que se pretendía resolver, valorando si el cálculo en el sistema ha facilitado la solución del problema.

En el lenguaje proposicional es posible describir sistemas industriales complejos, declarando las restricciones entre sus componentes. O declarar el esqueleto básico de algunos de nuestro razonamientos habituales. Para algunas de estas aplicaciones la Lógica Proposicional es suficientemente útil. 

Para otras aplicaciones es un formalismo insuficiente. Usualmente porque lo que se quiere describir, representar, incluye detalles diferenciales que el lenguaje proposicional no permite codificar de forma distinta: no es suficientemente expresivo. En el tema siguiente, Lógica de Predicados, se apreciará enseguida esta mayor capacidad de 'representar más detalles sobre los estados del mundo que se quieren analizar' y sobre cómo los cálculos en ese sistema manejan esa diversidad.
````
