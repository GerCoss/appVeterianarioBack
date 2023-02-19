 appVeterianarioBack
<p align="center">
  <a href="https://nodejs.org/es/" target="blank"><img src="https://upload.wikimedia.org/wikipedia/commons/d/d9/Node.js_logo.svg" width="200" alt="Nest Logo" /></a>
</p>



  <p align="center"> <a href="http://nodejs.org" target="_blank">Node.js</a> es un entorno de ejecución para JavaScript construido con V8, motor de JavaScript de Chrome.</p>
    <p align="center">

## Descripción

Backend de una aplicación para llevar el seguimiento de pacientes para veterinarios.

## Instalación

```bash
$ npm install
```

## Ejecutando la aplicación

```bash
# desarrollo
$ npm run dev
# producción
$ npm run start
```

## Variables de entorno necesarias.
| Variable de entorno | Ejemplo | Descripción |
| --- | --- | --- |
MONGO_URI | {uri} | Uri de la base de datos en Mongo
JWT_SECRET | cualquier-seed-para-jwt | Secret de nuestros JWTs
EMAIL_USER | algun-usuario | Usuario de la base de datos
EMAIL_PASS | algun-password | Password de la base de datos
EMAIL_HOST | algun-host | Host donde se encuentra la base de datos
EMAIL_PORT | algun-port | Puerto de la base de datos
FRONTEND_URL | {url} | Url donde corre el frontend
PORT | 4000 | Puerto donde correra la aplicación