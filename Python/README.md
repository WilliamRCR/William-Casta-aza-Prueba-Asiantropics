# 1. Mencione 3 normas pertenecientes a la guía de estilos PEP8 y brinde ejemplos de su uso e importancia.

Es una guía de estilo para Python que establece convenciones para escribir código Python legible y consistente.
3 de sus normas serían:

- Longitud de línea
Las líneas de código deben tener una longitud máxima de 79 caracteres y de 72 caracteres para los comentarios y cadenas de documentación, esto con el objetivo de mejorar le legibilidad del código en caso de revisión.

Ejemplo:
Esta línea está bien dentro del límite de 79 caracteres y se ajusta a la norma.

```
def funcion_de_ejemplo(parametro1, parametro2, parametro3, parametro4):
    resultado = parametro1 + parametro2 + parametro3 + parametro4
    return resultado
```


- Uso de espacios alrededor de operadores
Se debe usar un solo espacio alrededor de operadores binarios (+, -, *, /, etc.). Con el objetivo de facilitar la lectura de código y la identificación de operaciones en la lógica.
Ejemplo:
```
resultado = (a + b) * (c - d)

```
- Nombrado de variables y funciones
Los nombres de las funciones y variables deben seguir el estilo snake_case, mientras que los nombres de las clases deben seguir el estilo CamelCase. Para poder establecer una  separación entre los diferentes tipos de entidades de un código (funciones, variables y clases).
Ejemplo:

Correcto
```
def calcular_area_circulo(radio):
    pi = 3.14159
    return pi * radio ** 2

class MiClaseEjemplo:
    def metodo_ejemplo(self):
        pass
```

Incorrecto
```
def calcularAreaCirculo(radio):
    pi = 3.14159
    return pi * radio ** 2

class mi_clase_ejemplo:
    def metodoEjemplo(self):
        pass
```



# 2. Describa los tipos de datos mutables de Python:
Son aquellos cuyo contenido puede ser modificado sin la creación de nuevas instancias. Algunos de ellos son:
- Listas (list)
- Diccionarios (dict)
- Conjuntos (set)
- Arrays (array)

# 3. Describa los tipos de datos inmutables de Python:
Son aquellos cuyo contenido no puede cambiarse una vez es creado. Algunos ejemplos son:
- int
- float
- str
- bytes
- tuple

# 4. Complete la palabra reservada de python en el siguiente programa:
![Captura de pantalla 2024-09-04 182805](https://github.com/user-attachments/assets/3361deac-fc78-414c-bf32-b0b5f8a4535b)

elif

# 5. Cual de las opciones es equivalente al código de python mostrado?
![Captura de pantalla 2024-09-04 183402](https://github.com/user-attachments/assets/766f007d-613f-4764-9ea5-1bdfe093a693)

d.
