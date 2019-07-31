## Backend

```bash
npm init --yes
```

```bash
npm i express express-handlebars express-session method-override \
mongoose passport passport-local bcryptjs connect-flash
npm i nodemon -D
```

express: Node Framework
express-handlebars: Integracion de motor de plantillas
express-session: Crear y trackear sesiones
method-override: Extender funcionalidad de formularios (enviar metodos put y delete)
mongoose: Provee el conector para hacer queries a la base de datos
passport
passport-local
bcryptjs: Permite encryptar las credenciales
connect-flash: Enviar mensajes entre multiples vistas
nodemon: Does autoreload of node server

src/index.js: Archivo principal de la aplicación, arranca el servidor
src/database.js: tener una conexión a una base de datos y es usado por index.js

| src/
| | config/: Archivos de configuración de nuestra aplicacion
| | helpers/: Funciones que nuestro servidor va a usar (reutilisables)
| | models/: Definir los datos que vamos a almacenar en la DB
| | public/: Insertar todos los archivos estaticos (css,js,html,img,fuentes)
| | routes/: crear las URL o rutas de nuestro servidor
| | views/: todas la vistas de nuestra app
