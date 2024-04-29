# Para iniciar el proyecto, primero debe clonar el repositorio y ejecutar el comando para instalar las dependencias.

```bash
git clone 'Nombre del repositorio'
cd api-rest-movies-NodeJS
npm install
```

# Descripción

Este proyecto es una API REST que permite realizar operaciones CRUD sobre una base de datos de películas. La API permite obtener todas las películas, obtener una película por su id, agregar una nueva película, actualizar una película y eliminar una película.

# Iniciar el proyecto

En el archivo package.json se encuentra el script para iniciar el proyecto. Se puede ejecutar cualquiera de los scripts

- start-local -> Para inciar el proyecto en modo local
- start-bd-mysql -> Para iniciar el proyecto con una base de datos MySQL
- start-mongo -> Para iniciar el proyecto con una base de datos MongoDB

# Configuraciones

- En modo local se puede ejecutar el proyecto sin necesidad de configurar nada.
- En modo MySQL se debe configurar el archivo bd.js con los datos de la base de datos MySQL.
- En modo MongoDB se debe configurar el archivo /models/mongo.js con los datos de la base de datos MongoDB, cambiando la URL de conexión.

# Rutas

- GET /movies -> Obtiene todas las películas
- GET /movies/:id -> Obtiene una película por su id
- POST /movies -> Agrega una nueva película
- PUT /movies/:id -> Actualiza una película por su id
- DELETE /movies/:id -> Elimina una película por su id

# Para ejecutar el index.html se puede utilizar

```bash
  npx servor ./web
```










