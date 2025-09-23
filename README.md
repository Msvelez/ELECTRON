# ELECTRON
REPO Explicativo de la biblioteca ELECTRON en JS

¿Qué es Electron?

Electron es una biblioteca (framework) que permite crear aplicaciones de escritorio multiplataforma usando tecnologías web como HTML, CSS y JavaScript. Se basa en dos componentes principales:

Chromium, para mostrar la interfaz como si fuera una página web.
Node.js, para acceder al sistema operativo (archivos, procesos, etc.).
Esto permite que los desarrolladores web puedan crear aplicaciones de escritorio sin aprender un lenguaje nuevo como C++ o C#.

¿Qué problemas resuelve?

Electron resuelve varios desafíos del desarrollo tradicional de aplicaciones de escritorio:

Problema tradicional	¿Cómo lo resuelve Electron?
Cada sistema operativo requiere código distinto	Usa una sola base de código para Windows, macOS y Linux
Aprender múltiples lenguajes (C++, Java, etc.)	Usa JavaScript, HTML y CSS
Crear interfaces modernas y responsivas	Usa tecnologías web modernas (como React o Vue)
Acceso limitado al sistema desde una app web	Usa Node.js para acceder al sistema operativo

¿En qué tipo de proyectos se usa?

Electron es ideal para aplicaciones de escritorio que:
Necesitan funcionar en varios sistemas operativos (multiplataforma).
Quieren aprovechar el conocimiento web existente (HTML/CSS/JS).
Requieren una interfaz de usuario rica e interactiva.
Necesitan interactuar con el sistema de archivos, procesos u otras funciones nativas del sistema operativo.

Ejemplos de uso:

Editores de código: como Visual Studio Code.
Aplicaciones de mensajería: como Slack y Discord.
Herramientas de productividad: como Microsoft Teams, Trello, Notion.
Streaming y comunicación: como Twitch Desktop.

Componentes clave de Electron:

Chromium
Es un navegador web de código abierto desarrollado por Google.
Se usa para renderizar (mostrar) la interfaz de usuario de la app.
Es la misma base que usan Chrome, Edge y Brave.

Node.js

Entorno que permite ejecutar JavaScript fuera del navegador.
Permite hacer tareas como:
Leer y escribir archivos
Ejecutar procesos del sistema



Versión portátil
Acceder a bases de datos

Usar paquetes de npm
