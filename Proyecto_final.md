#Glosario final fundamentos de computación



## fundamentos de programación 



1. Compilador — Programa que traduce todo el código fuente a lenguaje máquina antes de ejecutarlo, generando un archivo ejecutable.
2. Intérprete — Programa que traduce y ejecuta el código fuente línea por línea, sin generar un archivo ejecutable previo.
3. Depurador (Debugger) — Herramienta que permite examinar la ejecución de un programa paso a paso para encontrar y corregir errores.
4. IDE — Entorno de Desarrollo Integrado; software que combina editor de código, compilador/intérprete, depurador y otras herramientas en un solo programa.
5. Editor de código — Programa diseñado para escribir y editar código fuente, generalmente con resaltado de sintaxis.
6. Biblioteca (Library) — Conjunto de funciones y recursos reutilizables que un programador puede incorporar en su código para realizar tareas específicas.
7. Framework — Estructura o esqueleto de código que define reglas y proporciona herramientas para desarrollar aplicaciones de forma más rápida y organizada.
8. API — Interfaz de Programación de Aplicaciones; conjunto de reglas que permite que distintos programas o sistemas se comuniquen entre sí.
9. Repositorio — Espacio donde se almacena y organiza el código fuente de un proyecto, junto con su historial de cambios.
10. Control de versiones — Sistema que registra y gestiona los cambios realizados en el código a lo largo del tiempo, permitiendo volver a versiones anteriores.
11. Git — Sistema de control de versiones distribuido, usado para rastrear cambios en el código y coordinar el trabajo entre varios desarrolladores.
12. GitHub — Plataforma en línea que aloja repositorios de Git y facilita la colaboración, el almacenamiento y la gestión de proyectos.
13. Rama (Branch) — Línea de desarrollo independiente dentro de un repositorio que permite trabajar en cambios sin afectar el código principal.
14. Commit — Registro de los cambios realizados en el código en un momento específico dentro del control de versiones.
15. Merge — Proceso de combinar los cambios de una rama con otra, uniendo el trabajo realizado por separado.
16. Callback — Función que se pasa como argumento a otra función y se ejecuta después de que esta termina o cuando ocurre un evento determinado.
17. Programación síncrona — Modelo en el que las instrucciones se ejecutan una tras otra, esperando que cada una termine antes de continuar con la siguiente.
18. Programación asíncrona — Modelo que permite ejecutar tareas sin esperar a que terminen otras, continuando el flujo del programa mientras se completan en segundo plano.
19. JavaScript — Lenguaje de programación interpretado, usado principalmente para dar interactividad a páginas web tanto en el navegador como en el servidor.
20. TypeScript — Lenguaje de programación desarrollado por Microsoft que extiende JavaScript añadiendo tipado estático, compilándose finalmente a JavaScript.

Conceptos básicos de programación (Algoritmo, Variable, etc.)
•	Real Academia Española / Fundéu. Diccionario de informática.
•	Joyanes Aguilar, L. (2008). Fundamentos de Programación: Algoritmos, Estructuras de Datos y Objetos. McGraw-Hill.
•	MDN Web Docs (Mozilla). Glosario de programación. https://developer.mozilla.org/es/docs/Glossary
•	freeCodeCamp. Programming Glossary. https://www.freecodecamp.org/
•	• GeeksforGeeks. Compiler vs Interpreter. https://www.geeksforgeeks.org/ 
•	 Visual Studio Code. Documentación oficial. https://code.visualstudio.com/docs 
•	 JetBrains. ¿Qué es un IDE?. https://www.jetbrains.com/
•	GitHub. GitHub Docs. https://docs.github.com/es
•	MDN Web Docs. JavaScript. https://developer.mozilla.org/es/docs/Web/JavaScript

 #Comandos básicos de Linux

1.	Pwd
¿Qué hace?
Muestra la ubicación exacta de la carpeta en la que estamos trabajando actualmente.
Sintaxis:
Pwd
Ejemplo:
Pwd
Resultado posible:
/home/daniel/documentos
Es útil para saber en qué parte del sistema de archivos nos encontramos.
2.	Ls
¿Qué hace?
Muestra los archivos y carpetas que existen dentro de la ubicación actual.
Sintaxis:
Ls [opciones] [ruta]
Ejemplo:
Ls
También podemos utilizar:
Ls -l
La opción -l muestra información más detallada sobre los archivos.
3.	Cd
¿Qué hace?
Permite cambiar de una carpeta a otra dentro del sistema.
Sintaxis:
Cd [ruta]
Ejemplo:
Cd Documentos
Para regresar a la carpeta anterior:
Cd ..
4.	Mkdir
¿Qué hace?
Crea una nueva carpeta o directorio.
Sintaxis:
Mkdir [nombre_de_carpeta]
Ejemplo:
Mkdir Tareas
Esto crea una carpeta llamada Tareas.
5.	Touch
¿Qué hace?
Puede crear un archivo vacío. También sirve para actualizar la fecha y hora de modificación de un archivo existente.
Sintaxis:
Touch [nombre_del_archivo]
Ejemplo:
Touch tarea.txt
Esto crea el archivo tarea.txt si todavía no existe.
6.	Cp
¿Qué hace?
Copia archivos o directorios de una ubicación a otra.
Sintaxis:
Cp [origen] [destino]
Ejemplo:
Cp tarea.txt respaldo.txt
Esto crea una copia de tarea.txt llamada respaldo.txt.
7.	Mv
¿Qué hace?
Sirve para mover archivos o carpetas. También puede utilizarse para cambiarles el nombre.
Sintaxis:
Mv [origen] [destino]
Ejemplo para cambiar un nombre:
Mv tarea.txt tarea_final.txt
En este caso, el archivo cambia de nombre.
8.	Rm
¿Qué hace?
Elimina archivos y, utilizando determinadas opciones, también puede eliminar directorios.
Sintaxis:
Rm [opciones] [archivo]
Ejemplo:
Rm tarea.txt
El archivo tarea.txt será eliminado.
 Es importante utilizar este comando con cuidado, ya que un archivo eliminado mediante rm normalmente no pasa por una papelera de reciclaje.
9.	Cat
¿Qué hace?
Permite mostrar en la terminal el contenido de uno o varios archivos. También puede utilizarse para concatenar archivos.
Sintaxis:
Cat [archivo]
Ejemplo:
Cat tarea.txt
La terminal mostrará el contenido de tarea.txt.
10.	Less
¿Qué hace?
Permite visualizar archivos de texto de manera interactiva, especialmente cuando son demasiado grandes para mostrarlos completos de una sola vez.
Sintaxis:
Less [archivo]
Ejemplo:
Less documento.txt
Podemos desplazarnos por el contenido y presionar q para salir.
11.	Head
¿Qué hace?
Muestra las primeras líneas de un archivo. Por defecto, normalmente muestra las primeras 10 líneas.
Sintaxis:
Head [opciones] [archivo]
Ejemplo:
Head documento.txt
Para mostrar las primeras 5 líneas:
Head -n 5 documento.txt
12.	Tail
¿Qué hace?
Muestra las últimas líneas de un archivo. Por defecto, normalmente muestra las últimas 10.
Sintaxis:
Tail [opciones] [archivo]
Ejemplo:
Tail documento.txt
También podemos indicar una cantidad específica:
Tail -n 5 documento.txt
Esto muestra las últimas cinco líneas.
13.	Clear
¿Qué hace?
Limpia el contenido visible de la terminal para que podamos trabajar con una pantalla despejada.
Sintaxis:
Clear
Ejemplo:
Clear
No elimina archivos ni información del sistema, solamente limpia la pantalla de la terminal.
14.	Echo
¿Qué hace?
Muestra un texto o el valor de una variable en la terminal.
Sintaxis:
Echo [texto]
Ejemplo:
Echo “Hola mundo”
Resultado:
Hola mundo
También puede utilizarse para escribir información en archivos mediante redirecciones.
15.	Man
¿Qué hace?
Abre el manual de un comando. Es una herramienta muy útil para conocer su funcionamiento, opciones y sintaxis.
Sintaxis:
Man [comando]
Ejemplo:
Man ls
Esto abre el manual del comando ls.
Para salir del manual normalmente se utiliza:
Q
16.	Whoami
¿Qué hace?
Muestra el nombre del usuario con el que estamos trabajando actualmente.
Sintaxis:
Whoami
Ejemplo:
Whoami
Resultado posible:
Daniel
Es especialmente útil cuando existen diferentes cuentas de usuario en el mismo sistema.
17.	Date
¿Qué hace?
Muestra la fecha y hora actuales del sistema.
Sintaxis:
Date
Ejemplo:
Date
Resultado posible:
Thu Sep 24 07:16:00 CST 2026
El formato exacto depende de la configuración del sistema.
18.	Grep
¿Qué hace?
Busca un texto o patrón determinado dentro de archivos o de información que recibe como entrada.
Sintaxis:
Grep [opciones] [patrón] [archivo]
Ejemplo:
Grep “Linux” documento.txt
Esto busca las líneas de documento.txt que contienen la palabra Linux.
19.	Find
¿Qué hace?
Busca archivos y directorios dentro de una ubicación determinada, utilizando criterios como nombre, tipo o fecha.
Sintaxis:
Find [ruta] [criterios]
Ejemplo:
Find . -name “tarea.txt”
El punto . indica que la búsqueda comenzará desde la carpeta actual.
20.	Sudo
¿Qué hace?
Permite ejecutar un comando utilizando los privilegios administrativos disponibles para el usuario, normalmente solicitando autenticación.
Sintaxis:
Sudo [comando]
Ejemplo:
Sudo apt update
En sistemas basados en Debian, este comando puede utilizarse para ejecutar apt update con privilegios administrativos.
 Debe utilizarse con cuidado, porque los comandos ejecutados con privilegios administrativos pueden modificar partes importantes del sistema.
GNU Project. GNU Coreutils Manual. https://www.gnu.org/software/coreutils/manual/coreutils.html⁠�
Linux man-pages Project. Linux man-pages. https://man7.org/linux/man-pages/⁠�
GNU Project. GNU Coreutils. https://www.gnu.org/software/coreutils/⁠�
Canonical. Ubuntu Documentation. https://documentation.ubuntu.com/⁠�
Debian Project. Debian Reference. https://www.debian.org/doc/manuals/debian-reference/⁠�

## Lists

Unordered lists use dashes, asterisks, or plus signs:

- Import files from GitHub, Dropbox, or Google Drive
- Export to Markdown, HTML, or PDF
- Drag and drop files directly into the editor

Ordered lists are numbered automatically:

1. Write your markdown
2. Preview the rendered output
3. Export or save to the cloud

Nested lists work too:

- Cloud integrations
  - GitHub repositories
  - Dropbox folders
  - Google Drive files
  - OneDrive and Bitbucket
- Local features
  - Auto-save to browser storage
  - Image paste from clipboard

## Task Lists

- [x] Set up the editor
- [x] Write some markdown
- [ ] Connect a cloud service
- [ ] Export the finished document

## Links and Images

Link to any page with [inline links](https://dillinger.io) or use [reference-style links][dillinger].

Images use a similar syntax:

![Placeholder](https://placehold.co/600x200/2B2F36/35D7BB?text=Your+Image+Here)

[dillinger]: https://dillinger.io

## Blockquotes

> The art of writing is the art of discovering what you believe.
>
> — Gustave Flaubert

Blockquotes can contain other markdown elements:

> **Tip:** Use `Cmd+Shift+Z` to enter zen mode for distraction-free writing.

## Code

Fenced code blocks support syntax highlighting:

```javascript
function greet(name) {
  return `Hello, ${name}.`;
}

console.log(greet("world"));
```

```python
def fibonacci(n):
    a, b = 0, 1
    for _ in range(n):
        a, b = b, a + b
    return a
```

## Tables

| Shortcut | Action |
|----------|--------|
| `⌘ ⇧ Z` | Toggle zen mode |
| `Escape` | Exit zen mode |
| `?` | Keyboard shortcuts |

Tables support alignment:

| Feature | Status | Notes |
|:--------|:------:|------:|
| Markdown editing | Active | Monaco-powered |
| Live preview | Active | Scroll-synced |
| Cloud sync | Available | 5 providers |
| PDF export | Available | Server-rendered |

## Footnotes

Dillinger supports extended markdown syntax including footnotes[^1] and definition lists.

[^1]: Footnotes appear at the bottom of the rendered preview.

## Math

Inline math: $E = mc^2$

Block equations:

$$
\sum_{i=1}^{n} i = \frac{n(n+1)}{2}
$$

---

*Your documents save automatically. Start writing.*
