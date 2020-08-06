# Qué es Node.js
Node.js es un entorno en tiempo de ejecución con las siguientes características:
- Está basado en javascript.
- Es asíncrono.
- Es de código abierto.
- Trabaja desde el lado del servidor.
- Trabaja con E/S de datos.
- Está preparado para programación orientada a eventos.
- Está basado en el motor V8 de Chrome.

# Qué es NPM
NPM (Node Package Manager) es el sistema gestor de paquetes que utiliza Node.js, el cual permite a Node.js trabajar con módulos predefinidos.

# Instalación de Node.js
La instalación de Node.js se puede hacer desde [su página web](https://nodejs.org/es/download/). Una vez instalado, para comprobar que está instalado, podemos utilizar el comando __node -v__ para ver la versión de Node.js que hay instalada. Si todo está correcto, se mostrará algo similar a lo siguiente:
```
$ node -v
v8.10.0
```

# Escribiendo código
Para tener todo el código organizado, lo primero que vamos a hacer es crear una carpeta con el nombre __webserverexpress__ donde guardaremos todas las carpetas y los ficheros necesarios. Desde la terminal, la creación de esta carpeta se haría mediante el siguiente comando:
```
$ mkdir webserverexpress
```
Una vez creada esta carpeta, nos meteremos dentro y crearemos el fichero __index.js__, el cual contendrá el código principal del servidor web. La creación del fichero dentro de la carpeta creada se haría mediante los siguientes comandos:
```
$ cd webserverexpress
$ touch index.js
```