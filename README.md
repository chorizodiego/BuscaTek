# BuscaTek

Un sistema de busqueda inteligente usando [MongoDB](https://www.mongodb.org/), [Express](http://expressjs.com/), 
[AngularJS](https://angularjs.org/) y [Node.js](https://nodejs.org/), tambien conocido como MEAN.

## Requerimientos

Ten estos paquetes instalados en tu sistema antes de correr todo.

- [Node.js](https://nodejs.org/en/download/)
- [MongoDB](https://www.mongodb.org/downloads)
- [SASS](http://sass-lang.com/install)
- [Grunt-cli](http://gruntjs.com/getting-started)
- [Bower](http://bower.io/#install-bower)

## Instalación y configuración.

Configura interactivamente el sitio y la base de datos. La base de datos debe estar corriendo desde antes.
```bash
$ git clone https://github.com/chorizodiego/BuscaTek
$ cd BuscaTek/Server
$ node init.js
```
Lo que esta entre parentesis son los valores por defecto, lo apropiado es usar esos.

* mongodb user: admin
* mongodb pass: (no poner nada)

<!---
$ npm install
$ cd client
$ bower install 
$ cd ..
```
-->

## Usando la aplicación

```bash
$ grunt
```

Ahora BuscaTek debería estar corriendo en `http://localhost:3000`.

