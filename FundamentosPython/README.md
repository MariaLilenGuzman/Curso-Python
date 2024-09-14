## Fundamentos de python

### Contenidos:
# Contenido

- [¿Qué es Python?](#que-es-python)
- [Principales características de Python](#Principales-características-Python)
- [¿Qué son las variables?](#variables)
- [Manipulación de cadenas de textos](#manipulacion-de-cadenas-de-textos)
- [Enteros, flotantes y booleanos](#enteros-flotantes-y-booleanos)
- [`print`](#print)
- [Operaciones de entrada/salida en consola](#operaciones-de-entrada-salida-en-consola)
- [Conceptos](#conceptos)
---

## ¿Qué es Python? <a name="que-es-python"></a>
Python es un lenguaje de programación de alto nivel, interpretado y de propósito general, creado por Guido van Rossum y lanzado por primera vez en 1991. Es conocido por su simplicidad y legibilidad, lo que lo hace accesible tanto para principiantes como para programadores experimentados. Además, Python es utilizado en una amplia variedad de campos como desarrollo web, ciencia de datos, inteligencia artificial, automatización, y más.
## Principales características de Python: <a name="Principales-características-Python"></a>
- **Interpretado**: Python no requiere compilación previa, ya que el intérprete ejecuta el código línea por línea, lo que facilita la depuración y el desarrollo rápido.
- **Sintaxis sencilla y legible**: Su diseño promueve escribir código limpio y fácil de entender, lo que reduce la complejidad y facilita el mantenimiento. 
    
- **Multiparadigma**: Soporta programación orientada a objetos, programación imperativa y funcional.
- **Tipado dinámico**: No es necesario declarar el tipo de una variable antes de usarla; Python lo asigna automáticamente según el valor asignado.
- **Gran comunidad y ecosistema**: Tiene una amplia comunidad de desarrolladores y bibliotecas (como NumPy, Pandas, Django, etc.) que extienden sus funcionalidades en diversas áreas.

## ¿Qué son las variables? <a name="variables"></a>
Las variables en programación son contenedores que almacenan datos o valores que se pueden usar y manipular a lo largo de un programa. En Python, las variables se crean al asignar un valor a un nombre utilizando el signo igual (=). A diferencia de algunos lenguajes de programación, en Python no necesitas declarar el tipo de dato de una variable, ya que es un lenguaje dinámico.

nombre = "Lilen"

edad = 30

En este ejemplo, hemos creado dos variables:

- nombre almacena una cadena de texto ("Lilen").
- edad almacena un número entero (30).

### Reglas para nombrar variables:
1. No pueden comenzar con un número. El nombre debe empezar con una letra o un guion bajo (_).

    - Correcto: nombre, _edad
    - Incorrecto: 1edad

2. No deben contener espacios. Si el nombre tiene varias palabras, se puede usar la convención de snake_case (separar palabras con guion bajo).

    - Correcto: mi_variable
    - Incorrecto: mi variable

3. No pueden ser palabras reservadas del lenguaje. Palabras como if, else, while, class no pueden usarse como nombres de variables porque tienen un significado especial en Python.

4. Sensibles a mayúsculas y minúsculas. Python distingue entre mayúsculas y minúsculas, por lo que nombre y Nombre son dos variables diferentes.

### Asignación de valores a variables:
Para asignar un valor a una variable en Python, simplemente usa el signo igual (=). El lado izquierdo del = es el nombre de la variable, y el lado derecho es el valor que quieres almacenar.

### Tipos de datos que puede almacenar una variable:
    - Números enteros (int): como 10, -5.
    - Números de punto flotante (float): como 3.14, -0.01.
    - Cadenas de texto (str): como "Hola", 'Lilen'.
    - Booleanos (bool): valores True o False.

**Las variables permiten reutilizar datos y trabajar con ellos a lo largo del código de manera flexible.**
## Manipulación de cadenas de textos <a name="manipulacion-de-cadenas-de-textos"></a>

Uno de los tipos más comunes en Python es el string o cadena de caracteres, que se puede representar de tres formas diferentes:
1. Usando comillas dobles:

   nombre = "Lilen"
2. Usando comillas simples:

   nombre = 'Lilen'
3. Usando comillas triples para cadenas multilínea:

   texto = '''Esto es
   una cadena
   multilínea'''
 
### Concatenación

Podemos sumar cadenas usando el operador `+`:

saludo = "Hola" + " " + "Lilen"

print(saludo)  # Resultado: "Hola Lilen"

### Repetición de cadenas

Es posible repetir una cadena usando el operador *:

nombre = "hola"

print(3 * nombre)  # Resultado: "holaholahola"

### Longitud de una cadena

Para obtener la longitud de una cadena (el número de caracteres), se usa la función len():

nombre = "Lilen"

print(len(nombre))  # Resultado: 5

### Indexación

Las cadenas en Python son indexadas, lo que significa que cada carácter tiene una posición numérica. La primera posición es 0 (cero).

Ejemplo de indexación:

name = "hola mundo"

print(name[0])  # Devuelve 'h'

También puedes acceder a los elementos de una cadena desde el final usando índices negativos. El último carácter es el índice -1:

print(name[-1])  # Devuelve 'o'

### Buenas prácticas

Es recomendable que si decides usar comillas simples para cadenas, mantengas ese estilo a lo largo del código. Lo mismo aplica si prefieres usar comillas dobles. Esto mejora la coherencia y legibilidad del código.

### Métodos de cadenas 

Los métodos son funciones asociadas a tipos de variables. En el caso de las cadenas, algunos de los métodos más útiles son:

- lower(): Convierte toda la cadena a minúsculas.
- upper(): Convierte toda la cadena a mayúsculas.
- strip(): Elimina los espacios en blanco al inicio y al final de la cadena.

## Enteros, flotantes y booleanos <a name="enteros-flotantes-y-booleanos"></a>
*(Aquí va la información sobre enteros, flotantes y booleanos)*

## print` <a name="print"></a>
*(Aquí va la información sobre el uso de `print`)*

## Operaciones de entrada/salida en consola <a name="operaciones-de-entrada-salida-en-consola"></a>
*(Aquí va la información sobre las operaciones de entrada/salida en consola)*

## Conceptos <a name="conceptos"></a>
 - **Sintaxis:**  se refiere a las reglas que dictan cómo debe estructurarse el código para que sea reconocido y ejecutado correctamente.
 - **Semántica:** se refiere al significado que el intérprete otorga a las instrucciones del código. Mientras que la sintaxis está relacionada con la estructura del código, la semántica describe lo que el código hace cuando se ejecuta.
 - **Indentación:** Una característica distintiva de Python es que usa la indentación (espacios o tabulaciones al principio de las líneas) para definir bloques de código, como las estructuras de control (if, for, etc.). A diferencia de otros lenguajes que usan llaves {}, Python requiere una indentación consistente, ya que es parte de su sintaxis.
