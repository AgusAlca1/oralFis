# Node.js y NPM
## Node.js
### ¿Qué es? 
En el pasado *JavaScript* (JS) era un lenguaje de programación únicamente por un motor de un navegador.
En el 2009, Ryan Dhal creó un entorno en el cual podía ejecutar *JavaScript* por fuera de un navegador. Lo hizo de la siguiente manera: al programa que escribió Ryan, le integro el *V8 de Chrome* (el motor de JS de ese navegador), el cual es código abierto y puede ejecutar con gran velocidad JS.
### ¿Cómo funciona?
NODE utiliza un **MODELO ASÍNCRONO Y ORIENTADO A EVENTOS**, lo que hace es que el procesamiento de una tarea no va a retrasar la ejecución de otras tareas, lo hace de manera liviana y eficiente. Está diseñado para construir aplicaciones en red escalables(la escalabilidad es la capacidad de una aplicación para manejar un número creciente de clientes o usuarios).

### ¿En qué áreas se usa?
Aplicaciones de una sola página (SPA): para construir una aplicación web con una experiencia similar a la de una aplicación de escritorio, Node.js es ideal. Ofrece un entorno eficiente para desarrollar SPAs.

Backend de redes sociales: LinkedIn, una red social líder, utiliza Node.js debido a su escalabilidad, el motor V8, una autenticación confiable y un enfoque basado en nodos.

Streaming de datos: Netflix, por ejemplo, para poder transmitir su contenido a millones de usuarios utiliza *Node.js*. Su naturaleza ligera, carga eficiente y velocidad lo hacen perfecto para aplicaciones de streaming de datos.


### Comando para ejecutar node.js
1. Posicionarse en la carpeta con el proyecto con extensión .js
2. Escribir en la consola ***node archivo.js***

## NPM
### ¿Qué es?
Node cuenta con su propio gestor de paquetes(es un sistema o conjunto de herramientas que se emplea para automatizar la instalación, actualización, configuración y utilización de programas) llamado **NPM** (Node Package Manager), considerado el sistema de librerías de código abierto más grande del mundo.

### ¿Por qué usar NPM?
1. Administrar las dependencias de tu proyecto, lo que incluye la instalación, actualización y eliminación de bibliotecas o programas de terceros.

2. Facilita el acceso a proyectos seguros de Node.js para el desarrollo de aplicaciones.

3. **NPM** te ayuda a desarrollar tus proyectos de manera más rápida y eficiente al proporcionar acceso a piezas de código ya creadas y probadas que otras personas han desarrollado y compartido.
4. Ofrece una amplia gama de herramientas disponibles de manera gratuita, lo que te permite elegir las que mejor se adapten a tus necesidades sin incurrir en costos adicionales.

5. Los comandos de npm son fáciles de aprender y utilizar, lo que simplifica el proceso de desarrollo y no requiere una curva de aprendizaje prolongada.

### Comandos útiles
1. npm install -g [nombre del paquete] (instala el paquete de forma global)
2. npm uninstall -g [nombre del paquete] (desinstala el paquete de forma global)
3. npm update -g [nombre del paquete] (actualiza el paquete de forma global)