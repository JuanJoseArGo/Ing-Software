# JSON y XML
<img src=/archivos/individual/actividad-01/JsonXml.png alt="drawing" width="200"/>

## Introducción

A principios de 1990 surgió el problema de que las máquinas pudieran entenderse entre sí. Entonces utilizaban diferentes sistemas operativos y sus programas estaban escritos en diferentes lenguajes de programación. Una de las soluciones fue crear el estándar XML. 

Sin embargo, XML presentaba problemas sobre todo cuando se trataba de trabajar con gran volumen de datos, puesto que el procesamiento se volvía lento. Surgieron entonces intentos para definir formatos que fueran más ligeros y rápidos para el intercambio de información. Uno de ellos fue JSON, promovido y popularizado a principios de los 2000 por Douglas Crockford.

Desde entonces JSON se caracteriza por reducir el tamaño de los archivos y el volumen de datos que es necesario transmitir. En la actualidad ambos se emplean para el intercambio de datos. 

# JSON

![Mi Imágen](/archivos/individual/actividad-01/json.png)

## Definicion (JSON)

JSON, cuyo nombre corresponde a las siglas **JavaScript Object Notation** o **Notación de Objetos de JavaScript**, es un formato ligero de *intercambio de datos*, que resulta sencillo de leer y escribir para los programadores y simple de interpretar y generar para las máquinas.

JSON es un formato de texto completamente independiente de lenguaje, pero utiliza convenciones que son ampliamente conocidos por los programadores, entre ellos:

- C
- C++
- C#
- JavaScript
- Python
entre otros.

Los JSON son cadenas - útiles cuando se quiere transmitir datos a través de una red. Debe ser convertido a un objeto nativo de JavaScript cuando se requiera acceder a sus datos. Esto no es un problema, dado que JavaScript posee un objeto global JSON que tiene los métodos disponibles para convertir entre ellos.

## Principales características (JSON)
Las principales características de un documento Json son:

- JSON es solo un formato de datos.
- Requiere usar comillas dobles para las cadenas y los nombres de propiedades. Las comillas simples no son válidas.
- Una coma o dos puntos mal ubicados pueden producir que un archivo JSON no funcione. 
- Puede tomar la forma de cualquier tipo de datos que sea válido para ser incluido en un JSON, no solo arreglos u objetos. Así, por ejemplo, una cadena o un número único podrían ser objetos JSON válidos.
- A diferencia del código JavaScript, en el que las propiedades del objeto pueden no estar entre comillas, en JSON solo las cadenas entre comillas pueden ser utilizadas como propiedades.

## Usos (JSON)
- **JSON es perfecto para almacenar datos temporales**. Los datos temporales pueden ser datos generados por el usuario, como un formulario enviado en un sitio web. JSON también se puede utilizar como formato de datos para cualquier lenguaje de programación para proporcionar un alto nivel de interoperabilidad.

- **Transferencia de datos entre sistemas**. La base de datos de un sitio web tiene la dirección de correo de un cliente, pero la dirección se tiene que verificar mediante una API para asegurarse de que sea válida. Envíe los datos de la dirección en formato JSON a la API del servicio de validación de direcciones.

- **Configurar datos para aplicaciones**. Al desarrollar aplicaciones, cada aplicación necesita las credenciales para conectarse a una base de datos, así como una ruta del archivo de registro. Las credenciales y la ruta del archivo se pueden especificar en un archivo JSON para que pueda ser leído y que esté disponible.

- **Modelos de datos complejos simplificados**. JSON simplifica los documentos complejos en componentes identificados como significativos mediante la conversión del proceso de extracción de datos en un archivo JSON predecible y legible por humanos.

## Ventajas y desventajas (JSON)

**Ventajas:** 

- Es autodescriptivo y fácil de entender.
- Su sencillez le ha permitido posicionarse como alternativa a XML.
- Es más rápido en cualquier navegador.
- Es más fácil de leer que XML.
- Es más ligero (bytes) en las transmisiones.
- Velocidad de procesamiento alta.
- Puede ser entendido de forma nativa por los analizadores de JavaScript.

**Desventajas:**

- Algunos desarrolladores encuentran su escueta notación algo confusa.
- No cuenta con una característica que posee XML: extensibilidad.
- No soporta grandes cargas, solo datos comunes.
- Para la seguridad requiere de mecanismos externos como expresiones regulares.

# XML

<img src=/archivos/individual/actividad-01/xml.png alt="drawing" width="350"/>

## Definición (XML)

Se trata simplemente de un tipo de **lenguaje de marcado** o conjunto de códigos (denominados etiquetas) que definen la estructura y el significado de los datos. De allí, que al crear un formato único y un lenguaje personalizado, puede utilizarse varias veces de distintas maneras en diferentes sistemas, independientemente de la plataforma o sistema operativo hardware que se esté usando. 
Se divide en dos partes; *prolog y body*. El primero, se trata de metadatos administrativos, como la declaración de tipo de documento XML o la instrucción de procesamiento opcional. Por otro lado, el segundo consiste en la estructura y el contenido, los cuales podemos encontrar fácilmente en los textos simples.

## Principales características (XML)

XML es un subconjunto de SGML que incorpora las tres características más importantes de este:

- Extensibilidad: estructura y validacion.
- Basado en texto.
- Orientado a los contenidos no presentación.
- Las etiquetas se definen para crear los documentos, no tienen un significado preestablecido.
- No es sustituto de HTML.
- No existe un visor genérico de XML.

## Usos (XML)

- **Facilita el intercambio de datos**ya que los datos XML están almacenados en formato de texto simple, lo que permite almacenar y compartir la información entre diferentes sistemas o aplicaciones de manera más rápida y sencilla. La segunda, porque si hay algo que caracteriza a los datos XML, es que los mismos pueden ser leídos por diferentes plataformas o sistemas que aún siendo incompatibles permiten a los desarrolladores intercambiar fácilmente los datos entre una y otra. 
- **Separa los datos de HTML** ya que pueden almacenarse en archivos XML separados, lo que hace más sencilla su edición cada vez que sea necesario. 
- **Simplifica el cambio a una nueva aplicación, sistema o plataforma** 
al almacenanarse en formato de texto simple, hacen más sencilla la futura expansión o actualización a un nuevo sistema de información, navegador o plataforma. 
- **Útil para crear nuevos idiomas en internet con diferentes tipos de fines** XML ha permitido la creación de diferentes idiomas, capaces de ser codificados por distintos tipos de máquinas de lectura. Así, podemos nombrar el RSS (usado en noticias), WAP y WML, XHTML, SMIL, entre otros. 


## Ventajas y Desventajas (XML)

**Ventajas:**

- Tiene un formato estructurado y fácil de comprender.
- Separa radicalmente la información o el contenido de su presentación o formato.
- Está diseñado para ser utilizado en cualquier lenguaje o alfabeto.
- Su análisis sintáctico es fácil debido a las estrictas reglas que rigen la composición de un documento.
- Tiene soporte a cualquier tipo de datos.
- Se pueden definir estructuras complejas y reutilizables.

**Desventajas:**

- El formato es sumamente estricto.
- Lleva más tiempo procesarlo.
- Complejidad de analizador (parser).
- Un error en cualquier parte del formato puede hacer que todo el documento sea inválido.

# Cuadro comparativo (JSON vs XML)

| Categoria      | JSON | XML     |
| :---        |    :----:   |          ---: |
|       | JSON es un (Notación de objetos de JavaScript) Es un estándar abierto basado en texto para el intercambio de datos.       | XML (lenguaje de marcado extensible) es un formato independiente de software-hardware para el intercambio de datos.   |
| Tipo   | Meta-lenguaje        | Lenguaje de marcado      |
| Complejidad      | Simple y facil de leer       | Mas dificil   |
| Orientacion   | Orientado a datos        |  Orientado a documentos      |
| Arrays      | Soporta matrices       | No compatible con matrices    |
| Extension   | .json        | .xml      |

# Ejemplos (JSON vs XML)

**Ejemplo 1**
![Mi Imágen](/archivos/individual/actividad-01/ejemplo1.png)
**Ejemplo 2**
Archivo JSON izquierda, XML derecha.
![Mi Imágen](/archivos/individual/actividad-01/ejemplo2.png)
**Ejemplo 3**
Archivo JSON izquierda, XML derecha.
![Mi Imágen](/archivos/individual/actividad-01/ejemplo3.png)

## Bibliografia 

- ¿Qué es JSON? (2021). Retrieved October 20, 2021, from Oracle.com website: https://www.oracle.com/mx/database/what-is-json/#link3

- Rocío González. (2021). ¿Qué es XML en programación? Te explicamos punto por punto de qué se trata esta herramienta. Retrieved October 20, 2021, from https://www.crehana.com website: https://www.crehana.com/ar/blog/desarrollo-web/que-es-xml/

- JSON: ¿Qué es y para qué sirve? (2019, November 10). Retrieved October 20, 2021, from NextU LATAM website: https://www.nextu.com/blog/que-es-json/

- Exes. (2021). XML ¿Qué es? | Manual de XML. Retrieved October 20, 2021, from Mundolinux.info website: https://www.mundolinux.info/que-es-xml.htm

‌

‌