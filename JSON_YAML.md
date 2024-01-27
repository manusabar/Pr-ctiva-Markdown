# YAML i JSON
## JSON
JSON (JavaScript Object Notation) es un formato ligero de intercambio de datos. Algunas de sus principales características son:
- Capacidad para codificar estructuras de datos sencillas y objetos.
- Formato de datos ligero.
- Uso de la sintaxis del lenguaje de programación estándar.
- Fácil lectura y escritura para los usuarios.
- Fácil de analizar y generar por parte de las máquinas.
- Puede tomar la forma de cualquier tipo de datos que sea válido para ser incluido en un JSON, no solo arreglos u objetos.

En resumen, JSON es un formato de texto que permite el acceso, almacenamiento e intercambio de datos entre aplicaciones web de manera sencilla y eficiente. Es una alternativa al lenguaje XML y se utiliza ampliamente en el diseño de sitios web, aplicaciones móviles y programas computacionales.
### Lenguajes de Programación Compatibles
1. JavaScript: Como Json se basa en la sintaxis de los objetos literales de JavaScript, es totalmente compatible con JavaScript y ampliamente utilizado en aplicaciones web basadas en este lenguaje.

2. Python: Python cuenta con una biblioteca llamada json que permite la manipulación y generación de datos Json de manera sencilla.

3. Java: Java proporciona la biblioteca org.json que permite trabajar con Json de forma nativa.

4. C#: El lenguaje de programación C# ofrece la biblioteca System.Text.Json que facilita el manejo de Json.

### Curiosidades sobre JSON
Json no es un acrónimo: A pesar de que las cuatro letras "Json" se pueden pronunciar como una palabra, no es un acrónimo. No significa "JavaScript Object Notation", sino que se utiliza como una forma abreviada de referirse al formato de datos.

Notación basada en llaves y valores: Json utiliza una sintaxis basada en llaves y valores para representar los datos. Los datos se organizan en pares de clave-valor, donde cada clave es una cadena y cada valor puede ser cualquier tipo de dato válido en Json.

Formato legible para los humanos: A diferencia de otros formatos de intercambio de datos como el XML, Json es mucho más legible para los humanos. La estructura de los datos es clara y concisa, lo que facilita su comprensión y manipulación.

### Ejemplo y reglas JSON
![](https://asanzdiego.github.io/curso-nivelacion-bigdata-2017/recursos/slides/img/json/json-02.png)

__UN JSON object está rodeado por llaves {}.
Los pares nombre-valor se agrupan por un colon (:) y separados por un coma (,).
Un array comienza con un corchete izquierdo y termina con un soporte derecho [].
Las comas finales y los ceros iniciales en un número están prohibidos.
Los formatos octal y hexadecimal no están permitidos.
Each llave dentro del JSON debe ser único y debe estar entre comillas dobles.
los boolean type coincide solo con dos valores especiales: true y false y los valores NULL están representados por el null literal (sin comillas)__.
___

## YAML

Un formato de serialización de datos para intercambiar datos estructurados entre aplicaciones y servicios de software. Da prioridad al uso humano antes que al de las aplicaciones.

El aspecto y la sintaxis de JSON y YAML son similares pero ligeramente diferentes.

A simple vista, el formato JSON se asemeja más a una máquina en su representación de datos que YAML. Un mensaje JSON incluye estos símbolos:

   -  Llaves para objetos
   -  Dos puntos para separar pares clave-valor
   -  Corchetes para matrices 
   -  Comillas para delimitar cadenas

JSON se desarrolló a partir de un pequeño subconjunto de JavaScript. Por tanto, su sintaxis hace que los documentos JSON se parezcan al código de programación.
 

A diferencia de JSON, el formato YAML se parece más a cómo alguien escribiría datos estructurados en papel. Se diseñó específicamente para que fuera más fácil de leer para los humanos. Utiliza lo siguiente:

   -  Sangría para representar objetos 
   -  Dos puntos para separar pares clave-valor
   -  Guiones para matrices
   -  Almohadillas para señalar un comentario

__YAML__ se creó originalmente para simplificar __XML__.
##Ejemplo de sintaxis  comparativo XML JSON y YAML
YAML ha ganado una fuerte presencia en determinados ámbitos de la computación debido a su legibilidad y soporte de comentarios. En particular, YAML es el principal formato de serialización de datos para archivos de configuración en muchas herramientas y servicios de automatización, DevOps e infraestructura como código (IaC). Por ejemplo, YAML se usa a menudo en archivos de Docker y Kubernetes.

YAML también se utiliza para escribir archivos de configuración en estas ofertas de Amazon Web Services (AWS)

![](https://www.maquinasvirtuales.eu/ipsoapoo/2020/02/kubernetes-crear-un-fichero-yaml-1.png)
