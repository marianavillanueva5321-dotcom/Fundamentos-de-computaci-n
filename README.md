# Glosario de Conceptos — Fundamentos de Computación

**Autora:** Mariana Villanueva
**Actividad Final de Unidad — Glosario de conceptos**

---

## 1. Fundamentos de programación

### 1. Algoritmo
Secuencia finita y ordenada de instrucciones u operaciones específicas que permiten resolver un problema o tomar una decisión.

**Ejemplo:**
```
INICIO
1) Buscar la sección de zapatos en la tienda.
2) Tomar un par de zapatos. ¿Son de fiesta?
   SÍ: ir al paso 3 — NO: volver al paso 2
3) ¿Hay de la talla adecuada?
   SÍ: ir al paso 4 — NO: volver al paso 2
4) ¿El precio es adecuado?
   SÍ: ir al paso 5 — NO: volver al paso 2
5) Comprar el par de zapatos.
FIN
```

### 2. Programa
Software que ejecuta tareas específicas, como un procesador de texto o un sistema operativo.

**Ejemplo:** Windows, el sistema operativo de Microsoft que gestiona el contenido del equipo mediante ventanas independientes que pueden verse de forma simultánea.

### 3. Código fuente
Conjunto de líneas de texto que expresan, en un lenguaje de programación determinado, los pasos que debe seguir el computador para ejecutar correctamente un programa.

**Ejemplo (Python):**
```python
print("Hello, World!")
```

### 4. Lenguaje de programación
Lenguaje formal destinado a la construcción de programas informáticos.

**Ejemplo:** BASIC (*Beginner's All-purpose Symbolic Instruction Code*), familia de lenguajes imperativos de alto nivel surgida en 1964.

### 5. Sintaxis
Conjunto de reglas que rigen la estructura de los símbolos, las palabras y la puntuación en los lenguajes de programación.

**Ejemplo (Python):**
```python
def saludo():
    print("Hola, mundo")
```

### 6. Variable
Unidad de datos que puede cambiar de valor; es la forma más simple de almacenamiento y representa una zona de memoria donde se guardan datos.

**Ejemplo (Perl):**
```perl
my $nombrecomp = "Prueba escrita";
print "Ejemplo visto, $nombrecomp";
```

### 7. Constante
Valor fijo que un programa no puede modificar mientras se está ejecutando.

**Ejemplo (C):**
```c
#define PI 3.141
const double Cpi = PI;
printf("Constante definida PI: %f\n", PI);
```

### 8. Tipo de dato
Define qué clase de valores puede almacenar una variable y cómo pueden manipularse. Los **datos de colección**, por ejemplo, permiten almacenar múltiples valores bajo una sola variable, útiles para manejar grandes volúmenes de información de forma organizada.

### 9. Operador
Símbolo que indica al lenguaje qué operación realizar entre uno o más valores.

**Ejemplo (operadores de asignación en JavaScript):**
```javascript
let contador = 0;
contador += 5; // Ahora contador vale 5
```

### 10. Expresión
Cualquier fragmento de código que puede evaluarse para producir un valor.

**Ejemplo:** `coste + 10`, `(base * altura) / 2`, `saldo_actual - retirada`.

### 11. Condicional
Sentencia que permite que un programa responda de distinta forma según la situación evaluada.

**Ejemplo (Python):**
```python
edad = int(input("Ingresa tu edad: "))
if edad >= 18:
    print("Eres mayor de edad")
```

### 12. Bucle
Estructura de control que permite ejecutar una misma serie de instrucciones varias veces mientras se cumpla una condición.

**Ejemplo (Python):**
```python
for i in range(5):
    print(f"Iteración número: {i}")
```

### 13. Función
Bloque de código que realiza una tarea específica y puede reutilizarse dentro de un programa.

**Ejemplo (pseudocódigo):**
```
ENTERO suma(ENTERO numUno, ENTERO numDos)
INICIO
    ENTERO resultado
    resultado = numUno + numDos
    RETORNA resultado
FIN
```

### 14. Parámetro
Variable que una función, procedimiento o subrutina recibe para poder operar.

**Ejemplo:**
```c
int sumar(int a, int b) {
    return a + b;
}
```
En `sumar(a, b)`, `a` y `b` son los parámetros de la función.

### 15. Argumento
Valor concreto que se pasa a una función al momento de llamarla, permitiéndole realizar cálculos o procesos personalizados.

**Ejemplo (Python):**
```python
def saludo(nombre):
    print("Hola,", nombre)

saludo("Sara")  # "Sara" es el argumento
```

### 16. Retorno
Resultado que, opcionalmente, una función puede devolver al finalizar su ejecución.

**Ejemplo (C):**
```c
int Suma(int a, int b) {
    return a + b;
}
int resultado = Suma(3, 5); // resultado = 8
```

### 17. Arreglo
Estructura de datos que permite almacenar un conjunto de elementos del mismo tipo bajo un solo nombre.

**Ejemplo:** `letras = {'a', 'b', 'c'};` — arreglo usado para almacenar caracteres individuales.

### 18. Objeto
Representación de una entidad del mundo real o un concepto abstracto, con propiedades (características) y métodos (comportamientos) propios.

**Ejemplo:** un objeto *Libro* con propiedades como título, autor, editorial y año de publicación, y métodos como abrir, cerrar y leer.

### 19. Método
Función definida dentro de una clase que representa el comportamiento de un objeto.

**Ejemplo (Python):**
```python
flota = [Coche("Audi", "A4", 2020), Coche("BMW", "Serie 3", 2021)]
for coche in flota:
    coche.cambiar_marca("Volkswagen")
```

### 20. Evento
Acción o suceso que un programa detecta y que dispara automáticamente un bloque de código preparado para responder.

**Ejemplo:** el clic del ratón sobre un botón, que abre un menú.

---

## 2. Herramientas de desarrollo y control de versiones

### 21. Compilador
Programa que traduce la totalidad del código fuente escrito en un lenguaje de alto nivel a lenguaje máquina de una sola vez, generando un ejecutable antes de la ejecución.

**Ejemplo:** el compilador `gcc` traduciendo un archivo `main.c` a un ejecutable del sistema operativo.

### 22. Intérprete
Programa que analiza y ejecuta el código fuente línea por línea en tiempo real, sin generar un ejecutable previo.

**Ejemplo:** el entorno de ejecución de Python procesando un archivo `.py` de forma secuencial e inmediata.

### 23. Depurador (Debugger)
Herramienta que permite inspeccionar, detener y rastrear la ejecución de un programa paso a paso para identificar y corregir errores.

**Ejemplo:** el panel de depuración de un IDE, que permite colocar *breakpoints* para revisar el valor de las variables en memoria.

### 24. IDE
Entorno de desarrollo integrado que agrupa en una sola interfaz herramientas esenciales para programar, como editor de código, depurador, compilador y gestor de proyectos.

**Ejemplo:** Visual Studio o IntelliJ IDEA, con autocompletado avanzado y herramientas integradas.

### 25. Editor de código
Programa de texto ligero diseñado específicamente para escribir y modificar código fuente, con resaltado de sintaxis y extensiones.

**Ejemplo:** Visual Studio Code o Sublime Text.

### 26. Biblioteca
Conjunto de funciones, rutinas o bloques de código reutilizables que los desarrolladores invocan para resolver tareas específicas sin reescribirlas desde cero.

**Ejemplo:** la biblioteca `Math` en JavaScript o `NumPy` en Python para cálculos matemáticos.

### 27. Framework
Estructura de trabajo estandarizada que proporciona cimientos, reglas de diseño y un flujo de control predefinido sobre el cual desarrollar aplicaciones.

**Ejemplo:** React o Angular para interfaces web, o Django para servicios backend.

### 28. API
Conjunto de reglas, protocolos y definiciones que permite que dos aplicaciones o sistemas se comuniquen e intercambien información entre sí.

**Ejemplo:** la API de Google Maps integrada en una plataforma de entregas para mostrar ubicaciones en tiempo real.

### 29. Repositorio
Espacio digital de almacenamiento donde se organizan los archivos, carpetas, documentos e historial de cambios de un proyecto de software.

**Ejemplo:** la carpeta de un proyecto estructurada y rastreada por un sistema de control de versiones.

### 30. Control de versiones
Sistema que registra de forma sistemática los cambios realizados sobre el código fuente a lo largo del tiempo, permitiendo revertir modificaciones o revisar estados anteriores.

**Ejemplo:** recuperar una versión previa del software tras detectar una falla en la versión actual.

### 31. Git
Sistema de control de versiones distribuido y de código abierto, diseñado para rastrear modificaciones en archivos de código de forma rápida y eficiente.

**Ejemplo:** usar `git status` o `git log` en la terminal para auditar el estado del código fuente local.

### 32. GitHub
Plataforma basada en la nube que aloja repositorios de Git y ofrece herramientas de colaboración, revisión de código y gestión de proyectos en equipo.

**Ejemplo:** publicar el código de un proyecto en una cuenta de GitHub para permitir la contribución remota de otros desarrolladores.

### 33. Rama
Línea de desarrollo independiente dentro de un repositorio que permite trabajar en nuevas características sin alterar el código principal.

**Ejemplo:** crear la rama `feature-login` para programar un módulo de acceso sin interferir con la rama estable `main`.

### 34. Commit
Confirmación y registro de un conjunto de cambios en el historial del repositorio, acompañado de un mensaje explicativo.

**Ejemplo:** `git commit -m "Se corrige la validación del formulario de registro"`.

### 35. Merge
Operación mediante la cual se combinan las modificaciones de una rama secundaria dentro de una rama principal o de destino.

**Ejemplo:** integrar los cambios finalizados en `feature-login` hacia la rama principal `main`.

### 36. Callback
Función que se pasa como argumento a otra función para ser ejecutada posteriormente, una vez completada una tarea o evento específico.

**Ejemplo:** una función de respuesta enviada como parámetro a un evento de clic, que actualiza la interfaz solo cuando el usuario presiona el botón.

### 37. Programación síncrona
Modelo de ejecución en el que las tareas se procesan de forma secuencial y bloqueante: cada instrucción debe finalizar antes de que comience la siguiente.

**Ejemplo:** un script que detiene la ejecución del sistema mientras lee por completo un archivo pesado del disco local.

### 38. Programación asíncrona
Modelo de ejecución que permite iniciar operaciones de larga duración sin bloquear el hilo principal, continuando con otras tareas mientras se espera la respuesta.

**Ejemplo:** una petición HTTP a un servidor remoto mientras la página web sigue respondiendo a las interacciones del usuario.

### 39. JavaScript
Lenguaje de programación interpretado, dinámico y orientado a objetos, ampliamente utilizado para crear interactividad en páginas web y entornos de servidor.

**Ejemplo:** un script en el navegador que valida los datos de un formulario antes de enviarlos.

### 40. TypeScript
Lenguaje de programación desarrollado por Microsoft que funciona como un superset tipado de JavaScript, añadiendo tipado estático y compilando a JavaScript puro.

**Ejemplo:**
```typescript
let edad: number = 20;
```

---

## Referencias

- Aho, A. V., Lam, M. S., Sethi, R., & Ullman, J. D. (2008). *Compiladores: Principios, técnicas y herramientas* (2a ed.). Pearson Educación.
- Chacon, S., & Straub, B. (2014). *Pro Git* (2a ed.). Apress.
- Mozilla Developer Network [MDN]. (2024–2026). *JavaScript, Asynchronous programming and Web APIs*. MDN Web Docs.
- Pressman, R. S., & Maxim, B. R. (2021). *Ingeniería del software: Un enfoque práctico* (9a ed.). McGraw-Hill.
- Somerville, I. (2019). *Ingeniería del software* (10a ed.). Pearson Educación.
- Raffino, E. (2025). *Algoritmo en informática*. Enciclopedia Concepto.
- Nueva Escuela Mexicana. (s. f.). *Programa*. nuevaescuelamexicana.org
- Raffino, E. (2025). *Programa informático*. Enciclopedia Concepto.
- Raffino, E. (2023). *Código fuente*. Enciclopedia Concepto.
- González, C. (s. f.). *Código fuente: Ejemplos y ejercicios prácticos*. Saberpunto.com
- Raffino, E. (2026). *Lenguaje de programación*. Enciclopedia Concepto.
- Meneses, N. (2024). *¿Qué es la sintaxis en programación y por qué es importante?*. Skillnest.
- Blanco, P. (s. f.). *Sintaxis*. Euroinnova.
- Lifeder. (2026). *Variable en programación: qué es, características, tipos, ejemplos*.
- LEOJIMZDEV. (s. f.). *Operadores en programación: guía clara y práctica*.
- Modo Debug. (s. f.). *Tipos de expresiones en programación*.
- Gómez, L. (s. f.). *Ejemplos condicionales en programación*.
- Gómez, L. (s. f.). *Ejemplos de bucles en programación: for, while y más*.
- Codeando Simple. (s. f.). *Funciones en programación: definición, ejemplos y ventajas*.
- Alegsa, L. (2025). *Definición de parámetro (programación)*.
- University College. (2025). *¿Qué es un argumento en programación?*. MSMK.
- Llamas, L. (s. f.). *Valor de retorno de una función en programación*.
- Significadosweb. (s. f.). *20 ejemplos de arreglos en programación: tipos, definición y análisis*.
- Ebac. (2022). *Objeto en programación: qué es y para qué sirve, características, ejemplos y tipos*.
- (s. f.). *Qué es un método en programación orientada a objetos*.
- Cazares, N. (2026). *¿Qué es un evento en programación?*. Algonova.
