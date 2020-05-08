# Proyecto de blog personal

### Front-end

El front-end fue creado con **ReactJs y Hooks**

##### Cosas importantes a destacar del proyecto

* Uso de queryString para poder convertir las urls con buscadores en objetos de js www.example.com/post?page=2&limit=10, devuelve {page=2, limit=10}
* Uso de Context para almacenar datos del usuario y poder usarlos en toda la aplicacion
* Uso de Hook para poder consumir el Context y poder usarlo en cualquier parte de la aplicacion
* Uso de JWT para poder hacer un sistema de login con el localStorage del navegador
* Uso de JWT para poder refrescar el Token de autentificación y seguir dentro de la aplicacion
* Uso de libreria react-dropzone para poder subir una imagen en un drag and drop
* Uso de libreria react-drag-sortable para poder mover objetos dentro de una lista y cambiarle la posicion
* Uso de la libreria tinymce-react, sirve como un editor de texto para la edicion de posts
* Uso de React Helment para manipular todo el header de la aplicacion

### Back-end

El back-end fue creado con **Node**

##### Cosas importantes a destacar del proyecto

* Utilizacion de nodemon dentro del back para tener un servidor que se actualize cuando se guarde
* Creacion de middleware para poder verificar si el usuario esta autentificado con JWT.
* Subir imagenes desde una peticion HTTP y verificarlo con File System.
* Ocupar el paquete de mongoose-paginate y ocuparlo en el modelo de post como plugin y despues usarlo en el controlador para traer los posts.
* Usar el paquete de connect-multiparty para poder subir un archivo en cierta localizacion del backend.
* Aprender a utilizar JWT en el back-end con la intencion de mandar el token de autentificacion con un refresh token para poder actualziar el token si esta en el horario extra de sesion.
