GPG para seres humanos.
=========

Taller de GnuPG para seres humanos - Flisol Bogota 2012

Este es el codigo fuente de la documentación creada para el taller de GPG que se dictara el 5 de mayo del 2012 a las 9:00am durante el Flisol Bogota 2012.

Aqui podra reportar cualquier error/comentario/sugerencia [creando un Issue](https://github.com/cronopio/tallergpg/issues)

Adicionalmente a esta documentación existen unas diapositivas para acompañar el taller e ir haciendo una introducción a los asistentes.

El publico objetivo de este taller es cualquier persona que dispona de un GNU/Linux y desee aprender a mejorar la seguridad en sus comunicaciones.

Corriendo este Codigo
---------------------
Este codigo esta hecho sobre la libreria de [Node.js](http://nodejs.org/) llamada [http-server](https://github.com/nodeapps/http-server) hecho por los asombrosos chicos de [Nodejitsu](http://www.nodejitsu.com/) esta libreria lo unico que hace es renderizar el [TiddlyWiki](http://tiddlywiki.com/) en lo que esta hecho toda esta documentación.

Asi que si desea correr esto como un servidor web y permitir la lectura por los demas equipos en red deberá tener [Node.js](http://nodejs.org/) y [NPM](http://npmjs.org/) funcionando corrrectamente y ejecutar el comando:

```
npm start
```
Podra acceder al wiki como **solo lectura** entrando a ```http://localhost:8080```

Tambien es posible correr unicamente el TiddlyWiki desde el navegador directamente:
```
firefox ./public/index.html
```

Modificando el wiki
-------------------
Puede abrir el TiddlyWiki en **modo escritura** abriendolo directamente desde el navegador:
```
firefox ./public/index.html
```

Subir los cambios a este repositorio
------------------------------------
Primero debe estar familiarizado con [Git](http://git-scm.com/) y con [GitHub](https://github.com) asi que inicie por alli.
Cuando tenga claro los conceptos básicos de Git, simplemente haga un *fork* de este proyecto haciendo click en el boton de mas arriba.
Cuando ya tenga su propio fork entonces cree un nuevo *branch* y haga sus cambios alli, haga commit y demas cosas y por ultimo de click en el boton *Pull Request* que vera en su fork.
Tratare de integrar su trabajo lo mas pronto posible.
De antemano agradezco cualquier tipo de colaboración.
