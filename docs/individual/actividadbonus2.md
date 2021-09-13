# ¿Que es UML?

## Descripción

En el año de 1994 nació una nueva técnica de especificación para los sistemas: *UML*. Creado por Grady Booch (autor del método Booch), James Rumbarugh (autor del método OMT) e Ivar Jacobson (autor de los métodos OOSE y Objectory), UML es un lenguaje para hacer modelado de sistemas, es un lenguaje grafico que permite visualizar, especificar, construir y documentar un sistema de software. 

Las siglas UML significa Unified Modeling Language, es un lenguaje respaldad por el OMG (Object Management Group). La primera versión 1.0 de UML fue liberada en enero de 1997 y hasta la actualidad es el lenguaje de modelado de sistemas de software más conocido y utilizado. UML ofrece un estándar para describir un "plano" del sistema (modelo), incluyendo aspectos conceptuales tales como procesos de negociación y funciones del sistema, y aspectos concretos como expresiones de lenguajes de programación, esquemas de bases de datos y componentes de software reutilizables.


UML es un lenguaje de modelado que contiene modelos y esos modelos son utilizados para describir algo y comunicar los resultados del uso del método. El lenguaje de modelo consiste de vistas, diagramas, elementos de modelo, los símbolos utilizados en los modelos y un conjunto de mecanismos generales o reglas que indican cómo utilizar los elementos. Las reglas son sintácticas, semánticas y pragmáticas. UML no es programación, solo se diagrama la realidad de una utilización en un requerimiento.

En la versión UML 2.0 existen 13 tipos de diagramas.

![Mi Imágen](/archivos/individual/actividad-01/umlogo.png)

## Descripción diagramas
**Diagramas de estructura** enfatizan en los elementos que deben existir en el sistema modelado:

- *Diagrama de clases* :
Si los objetos tienen un comportamiento común o la misma estructura, pueden clasificarse (asignarse a una clase). La clase es, por tanto, un elemento simplificador (abstracción) para la representación visual. Las clases y los objetos están conectados entre sí mediante interfaces. El diagrama de clase muestra todos estos componentes y sus interrelaciones.
- *Diagrama de componentes:*
Un componente es un módulo que está aislado del sistema externo e interactúa con otros componentes mediante interfaces definidas. Es un subformulario de la clase. Por lo tanto, las características estructurales, como las operaciones y los atributos, definen el componente con mayor precisión. El componente contiene varios componentes. Estos pueden ser de nuevo componentes, pero también clases, subsistemas o partes. Hay dos opciones de visualización diferentes para el modelado: Black Box o caja negra (el contenido está oculto) y White Box o caja blanca (el contenido es visible).
- *Diagrama de objetos:*
El diagrama de objetos tiene una estructura similar a la del diagrama de clases. Cuando el nombre aparece en el diagrama de clase, el diagrama de objeto especifica el nombre de la instancia junto con el nombre del clasificador/categoría.
- *Diagrama de estructura compuesta:*
Los objetos pertenecen a clases. Estos, a su vez, también pueden clasificarse. Estas metaclases se denominan clasificadores en UML. El diagrama de estructura de la composición representa las partes y conectores de un clasificador. Las partes son siempre parte del todo, incluso si no son necesarias para completar el clasificador. Los conectores son las conexiones entre las partes. Las características o servicios que requieren componentes externos al clasificador envían las piezas a través de una interfaz.
- *Diagrama de paquetes:*
Un paquete agrupa elementos como interfaces o clases en un espacio de nombres. Los paquetes (packages) también pueden fusionarse con otros paquetes (fusión de paquetes), importarlos (importación de paquetes) o contener otros paquetes (subpaquetes). Los paquetes estructuran el contenido del diagrama jerárquicamente como en un diagrama de árbol.

**Diagramas de comportamiento** enfatizan en lo que debe suceder en el sistema modelado:

- *Diagrama de actividades:*
Las actividades consisten en una red de acciones que se relacionan entre sí mediante flujos de datos y de control. El Diagrama de actividades muestra cómo funcionan estos casos de uso.
- *Diagrama de casos de uso:*
El diagrama de casos de uso muestra el comportamiento que se esperará de un sistema más adelante. Este modelo no solo es adecuado para sistemas de software, sino también, por ejemplo, para procesos esperados en las relaciones comerciales. El caso de uso involucra a un actor (humano o sistema) con un objetivo. El diagrama normalmente tiene como nombre el objetivo. Los diferentes casos de uso dentro del sistema cumplen el objetivo del actor.
- *Diagrama de estados:*
Una máquina de estados, también llamada autómata finito, representa un conjunto finito de estados en un sistema. Si se cumple una condición definida en el sistema (se detona un desencadenante), se produce una situación correspondiente. Esto puede incluir actividades o interacciones. Bajo UML 2.0, un estado representa esta situación. Los estados se consideran como nodos (inglés: vértices) y se muestran como rectángulos con esquinas redondeadas. Además, el diagrama de máquina de estados modela las transiciones de un estado (nodo fuente) a otro (nodo destino). 

**Diagramas de Interacción**, un subtipo de diagramas de comportamiento, que enfatiza sobre el flujo - de control y de datos entre los elementos del sistema modelado:

- *Diagrama de secuencia:*
Como diagrama de interacción, el diagrama de secuencia representa el intercambio de mensajes entre objetos. El tipo de diagrama UML modela estos objetos como las llamadas líneas de vida. En este sentido, es similar a otros diagramas de comportamiento como el diagrama de actividad. Sin embargo, a diferencia de estos, el diagrama de secuencia no se utiliza para obtener una visión general del comportamiento de un sistema, sino para presentar un posible comportamiento entre muchos otros en detalle. Prescribe una cronología. Una línea discontinua representa el curso del tiempo.
- *Diagrama de comunicación:*
Al igual que el diagrama de secuencia, el diagrama de comunicación modela una transferencia de mensajes. Sin embargo, este diagrama UML no utiliza líneas discontinuas para la secuencia de tiempo, sino que numera las secuencias con números y letras. Estos llamados términos de secuencia se encuentran encima de una flecha con la punta apuntando hacia el receptor. Los números representan el orden en que se envían los mensajes, las letras representan el nivel jerárquico (como se muestra en la figura siguiente).
- *Diagrama de tiempos (UML 2.0):*
El diagrama de tiempos permite mostrar el comportamiento de los sistemas en detalle en función de la secuenciación temporal. Los sistemas en tiempo real, por ejemplo, tienen que manejar ciertos procesos dentro de un cierto período de tiempo. UML 2.0 modela el diagrama de temporización como un diagrama bidimensional con un eje x y un eje y para representar mejor el plano temporal. Con este subformulario del diagrama de secuencia, los estados de los objetos se encuentran en el eje y las secuencias de tiempo asignadas a ellos se ejecutan a lo largo del eje y.

## Diagrama de objetos

Un diagrama de objetos UML representa una instancia específica de un diagrama de clases en un momento determinado en el tiempo. Se enfoca en los atributos de un conjunto de objetos y cómo esos objetos se relacionan entre sí. 

No obstante, los diagramas de objetos no se limitan a casos de uso bancarios, ya que se puede crear fácilmente un diagrama de objetos para árboles genealógicos, departamentos corporativos o cualquier otro sistema con partes interrelacionadas.

Los diagramas de objetos son sencillos de crear: se componen de objetos, representados por rectángulos, conectados mediante líneas.

![Mi Imágen](/archivos/individual/actividad-01/diagramaOBJ.png)

- Objetos
Los objetos son instancias de una clase. Son representados con un rectángulo, que contiene el nombre del objeto y
su clase subrayadas y separadas por dos puntos. 

- Atributos de clases
Los atributos de clases se muestran en un compartimento en la parte inferior del nombre del objeto.

- Enlaces
Los enlaces son líneas que conectan dos figuras de un diagrama de objetos entre sí.

Un diagrama de objetos resulta muy útil para cuando queremos hacer una revisión de una iteración especifica de un sistema general o para tener la vista de nivel alto de un sistema.

## Diagrama de paquetes

Los diagramas de paquetes son diagramas estructurales que se emplean para mostrar la organización y disposición de diversos elementos de un modelo en forma de paquetes. Un paquete es una agrupación de elementos UML relacionados, como diagramas, documentos, clases o, incluso, otros paquetes. Cada elemento está anidado dentro de un paquete, que se representa como una carpeta de archivos dentro del diagrama, y que luego se organiza jerárquicamente dentro del diagrama. Los diagramas de paquetes se usan con frecuencia para proporcionar una organización visual de la arquitectura en capas dentro de cualquier clasificador UML, por ejemplo, un sistema de software.

Cada diagrama incluye únicamente dos símbolos:

- Paquete:
Agrupa elementos comunes basados en datos, comportamientos o interacciones de los usuarios.

- Dependencia:
Muestra la relación entre un elemento (paquete, elemento nombrado, etc.) y otro.

![Mi Imágen](/archivos/individual/actividad-01/diagramaPAQ.png)

### Componentes básicos

- Paquete: Un espacio de nombres empleado para agrupar los elementos relacionados lógicamente dentro de un sistema. Cada elemento contenido dentro del paquete debe ser un elemento empaquetable y tener un nombre único.

- Elemento empaquetable: Un elemento nombrado, posiblemente de propiedad directa de un paquete. Pueden incluir eventos, componentes, casos de uso y los propios paquetes. Los elementos empaquetables también pueden representarse como un rectángulo dentro de un paquete, rotulados con el nombre correspondiente.

- Dependencias: Representación gráfica de cómo un elemento (o un conjunto de elementos) depende de otro o influye a otro. Las dependencias se dividen en dos grupos: dependencias de acceso y de importación. (Consulta la próxima sección para más información).

- Importación de elemento: Relación dirigida entre un espacio de nombres de importación y un elemento empaquetable importado. Se emplea para importar ciertos elementos sin recurrir a una importación de paquete y sin publicarlo dentro del espacio de nombres. 

- Importación de paquete: Relación dirigida entre el espacio de nombres de importación y un paquete importado. Este tipo de relación dirigida añade los nombres de los integrantes del paquete importado en su propio espacio de nombres

- Fusión de paquetes: Relación dirigida en la que los contenidos de un paquete se extienden según los contenidos de otro paquete. En esencia, el contenido de dos paquetes se combina para producir un nuevo paquete.

### Dependencias
Cada dependencia se representa como una línea de conexión con una flecha que representa el tipo de relación entre dos o más elementos. 

Hay dos tipos principales de dependencias:

- Acceso: Indica que un paquete requiere la asistencia de las funciones de otro paquete.
- Importación: Indica que la funcionalidad se ha importado de un paquete a otro.

Las dependencias también se pueden desglosar con más detalle en las siguientes categorías:
- Uso: Ocurre cuando un elemento nombrado necesita otro elemento para su plena definición e implementación. Ejemplo: cliente y proveedor.
- Abstracción: Relaciona dos elementos que representan el mismo concepto en distintos niveles de abstracción dentro del sistema (por lo general, una relación entre cliente y proveedor).
- Implementación: Muestra la implementación de un artefacto para un objetivo de implementación.

Estos diagramas proporcionan una visualización clara de la estructura jerárquica de los distintos elementos UML dentro de un sistema dado, además que permiten simplificar diagramas de clases complejos en gráficos bien ordenados.
Son útiles en sistemas a gran escala y pueden actualizarse fácilmente a medida que los sistemas y los proyectos evolucionan.

## Diagrama de comunicación
Se utilizan para mostrar cómo interactúan los objetos para efectuar el comportamiento de un guión de uso concreto, o una parte de un guión de uso. Junto con los diagramas de secuencia, los diseñadores utilizan los diagramas de comunicación para definir y aclarar los roles de los objetos que efectúan un flujo de sucesos concreto de un guión de uso. Son el origen principal de información que se utiliza para determinar las responsabilidades y las interfaces de clases.

Un diagrama de comunicación muestra las relaciones entre los objetos. Además de que expresan una información similar, pero de modos diferentes. Los diagramas de comunicación muestran las relaciones entre objetos y son mejores para comprender todos los efectos en un objeto determinado para el diseño de procedimiento.

Tienden a ser más adecuados para las tareas de análisis. Específicamente, tienden a ser más adecuados para describir interacciones más sencillas de números más pequeños de objetos. 

![Mi Imágen](/archivos/individual/actividad-01/diagramaCOM.png)

**Objetos:**
Se representa con un símbolo de objeto que muestra el nombre del objeto y su clase subrayada, separados por dos puntos:

-NombreObjeto : NombreClase 

Puede utilizar objetos en diagramas de comunicación de los modos siguientes:

-  La clase de un objeto puede estar sin especificar. Habitualmente, crea un diagrama de comunicación con objetos primero y especifica sus clases posteriormente.
- Los objetos pueden no tener nombre, pero debería nombrarlos si desea discriminar diferentes objetos de la misma clase.
- La clase de un objeto puede representarse en un diagrama de comunicación, si participa activamente en la interacción.

**Actores:**
Normalmente, una instancia de actor se produce en el diagrama de comunicación, como la parte que invoca la interacción. Si dispone de varias instancias de actor en el mismo diagrama, intente mantenerlas en la periferia del diagrama.

**Enlaces:**

Es una relación entre objetos a través de la cual se pueden enviar mensajes. En diagramas de comunicación, un enlace se muestra como una línea sólida entre dos objetos.
Un objeto interactúa o navega con otros objetos a través de sus enlaces con estos objetos.
Los flujos de mensaje se conectan a enlaces mediante **mensajes**.
**Mensajes:**
Es una comunicación entre objetos que transfiere información con la expectativa de que esa actividad se llevará a cabo. Se muestra como una flecha etiquetada junto a un enlace. La flecha dirige a lo largo del enlace en la dirección del objeto de destino (el que recibe el mensaje). La flecha está etiquetada con el nombre del mensaje, y sus parámetros. La flecha también puede estar etiquetada con un número de secuencia para mostrar la secuencia del mensaje en la interacción global. Los números de secuencia suelen utilizarse en los diagramas de comunicación, porque son el único modo de describir la secuenciación relativa de los mensajes.


## Bibliografia 
- Que es UML. (2021). Retrieved September 13, 2021, from Unam.mx website: http://profesores.fi-b.unam.mx/carlos/aydoo/uml.html
- UML - EcuRed. (2021). Retrieved September 13, 2021, from Ecured.cu website: https://www.ecured.cu/UML#Diagramas
- Material de soporte: Diferencias entre UML 1.x y UML 2.0. (2021). Retrieved September 13, 2021, from Cgr.go.cr website: https://cgrw01.cgr.go.cr/rup/RUP.es/SmallProjects/core.base_rup/guidances/supportingmaterials/differences_between_uml_1_x_and_uml_2_0_CA70F2E6.html
- IONOS Digital Guide. (2018, October 26). UML, lenguaje de modelado gráfico. Retrieved September 13, 2021, from IONOS Digitalguide website: https://www.ionos.mx/digitalguide/paginas-web/desarrollo-web/uml-lenguaje-unificado-de-modelado-orientado-a-objetos/

‌

‌