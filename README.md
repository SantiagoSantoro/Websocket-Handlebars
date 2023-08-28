# Websockets Real-Time Product Management

Este proyecto es una implementación de gestión de productos en tiempo real utilizando WebSockets y Node.js. Permite a los usuarios agregar productos y ver la lista de productos actualizada en tiempo real.

## Características

- Agregar productos mediante un formulario.
- Ver la lista de productos actualizada en tiempo real utilizando WebSockets.
- Interfaz de usuario amigable.

## Tecnologías Utilizadas

- Node.js
- Express.js
- Socket.IO
- Handlebars (motor de plantillas)
- HTML, CSS

## Instalación

1. Clona este repositorio en tu máquina local.

2. Instala las dependencias con el siguiente comando: npm install


3. Inicia el servidor con el siguiente comando: npm run dev


4. Abre tu navegador web y visita [http://localhost:8080](http://localhost:8080/realtimeproducts) para acceder a la aplicación.

## Uso

1. Ingresa a la aplicación a través del navegador.

2. Agrega nuevos productos utilizando el formulario provisto.

3. La lista de productos se actualizará automáticamente en tiempo real a medida que se agreguen nuevos productos.

## Estructura del Proyecto

- `src/`: Contiene el código fuente de la aplicación.
- `app.js`: Configuración y ejecución del servidor Express y Socket.IO.
- `utils.js`: Contiene utilidades para manejar rutas y directorios.
- `routes/views.js`: Maneja las rutas para las vistas.
- Otros archivos y carpetas relacionados.

- `public/`: Contiene archivos públicos como estilos CSS y archivos estáticos.

- `views/`: Contiene las plantillas de Handlebars para las vistas.

- `manager/`: Contiene lógica de gestión de productos.

## Contribuciones

Las contribuciones son bienvenidas. Si encuentras un error o tienes una mejora, no dudes en abrir un "Issue" o enviar un "Pull Request".

## Licencia




