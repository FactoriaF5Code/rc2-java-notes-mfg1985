Las variables son contenedores para almacenar valores de datos.

En Java, hay diferentes tipos de variables, por ejemplo:

String- almacena texto, 
        como "Hola". Los valores de las cadenas están rodeados de comillas dobles
int- almacena números enteros (números enteros), 
        sin decimales, como 123 o -123
float- almacena números de coma flotante, 
        con decimales, como 19,99 o -19,99
char- almacena caracteres individuales,
         como "a" o "B". Los valores de caracteres están rodeados de comillas simples
boolean- almacena valores con dos estados: verdadero o falso


Para crear una variable, debe especificar el tipo y asignarle un valor.
También puede declarar una variable sin asignar el valor, y asignar el valor más tarde.
Tenga en cuenta que si asigna un nuevo valor a una variable existente, sobrescribirá el valor anterior.

VARIABLES FINALES:

Si no desea que se sobrescriban los valores existentes, usaremos la palabra clave final (esto declarará la variable como "final" o "constante", lo que significa que no se puede cambiar y es de solo lectura)

VARIABLE DE VISUALIZACION:

El método println() se utiliza a menudo para mostrar variables.
Para convinar variables utilizaremos el "+".
También puedes usar el carácter "+" para agregar una variable a otra variable.
Para valores numéricos, el carácter "+" funciona como un operador matemático.

DECLARAR MUCHAS VARIABLES:

Para declarar más de una variable del mismo tipo, puede usar una lista separada por comas.
Tambien se puede asignar el mismo valora a varias variables.

Todas las variables de Java deben identificarse con nombres únicos.

Estos nombres únicos se llaman identificadores.


IDENTIFICADORES:

Los identificadores pueden ser nombres cortos (como x e y) o nombres más descriptivos (edad, suma, volumen total).

Se recomienda utilizar nombres descriptivos para crear un código comprensible y mantenible.

Las reglas generales para nombrar variables son:

Los nombres pueden contener letras, dígitos, guiones bajos y signos de dólar
Los nombres deben comenzar con una letra
Los nombres deben comenzar con una letra minúscula y no pueden contener espacios en blanco
Los nombres también pueden comenzar con $ y _ (pero no lo usaremos en este tutorial)
Los nombres distinguen entre mayúsculas y minúsculas ("myVar" y "myvar" son variables diferentes)
Palabras reservadas (like Java keywords, such as int or boolean) no se pueden usar como nombres.