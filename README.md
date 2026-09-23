# 2026---TP2---G05
### 5ºA Infomática 2026
## Intrgrantes
- Francisco Jozuvaitis
- Luciano Parente
- Julián Décima
- Moisés Ticona
- Florencia De La Rosa

# Introducción

## ¿Qué es la aplicación?

Esta aplicación WEB es un sistema desarrollado para facilitar y mejorar la realización de distintas tareas de manera rápida y sencilla. La aplicación cuenta con una interfaz accesible desde un navegador WEB y permite a los usuarios interactuar con sus diferentes funcionalidades.

El proyecto está compuesto por diferentes elementos que trabajan en conjunto para permitir su correcto funcionamiento, como la interfaz de usuario, el servidor y, dependiendo de las necesidades de la aplicación, una base de datos.

### ¿Para qué sirve?

La aplicación tiene como finalidad ofrecer una solución digital a una necesidad específica, permitiendo que los usuarios puedan realizar las acciones correspondientes de forma organizada y eficiente.

A través de la aplicación, el usuario puede acceder a sus diferentes funcionalidades mediante una interfaz WEB, sin necesidad de instalar un programa adicional en su computadora.

### Funcionamiento general

Para utilizar la aplicación, el usuario debe ingresar desde un navegador WEB. Una vez dentro, puede navegar por las diferentes secciones y utilizar las funcionalidades disponibles.

La aplicación procesa las acciones realizadas por el usuario y muestra los resultados correspondientes en la interfaz.

### Objetivo de la aplicación

El objetivo principal de la aplicación es brindar una herramienta WEB que permita a los usuarios realizar las tareas para las que fue diseñada de una manera rápida, sencilla y organizada. Se busca facilitar el acceso a las distintas funcionalidades desde un mismo lugar, evitando procesos innecesarios y haciendo que la interacción sea clara y fácil de entender.

Además, la aplicación busca mejorar la experiencia del usuario mediante una interfaz simple e intuitiva, permitiendo que pueda utilizar sus funciones sin necesidad de conocimientos avanzados. De esta manera, se pretende ofrecer una solución práctica y accesible para resolver la necesidad planteada por el proyecto.

# Arquitectura de la aplicación

La aplicación utiliza una arquitectura web de tres capas, separando la interfaz de usuario, la lógica de negocio y la persistencia de datos.

## Componentes principales

### Frontend

Es la capa con la que interactúa el usuario. Se encarga de:

- Mostrar las páginas y componentes de la aplicación.
- Gestionar la interacción del usuario.
- Realizar solicitudes al backend mediante una API.
- Validar y mostrar información recibida del servidor.

### Backend

Es el encargado de procesar las solicitudes provenientes del frontend. Sus principales responsabilidades son:

- Exponer una API para la comunicación con el frontend.
- Implementar la lógica de negocio.
- Validar y procesar los datos recibidos.
- Gestionar la autenticación y autorización.
- Comunicarse con la base de datos.

### Base de datos

Almacena de forma persistente la información de la aplicación, como usuarios, configuraciones y datos generados por los usuarios.

## Flujo de comunicación

El usuario interactúa con la aplicación a través del frontend. Cuando realiza una acción, el frontend envía una solicitud al backend mediante una API utilizando HTTP/HTTPS.

El backend recibe la solicitud, valida los datos y ejecuta la lógica de negocio correspondiente. Cuando necesita consultar o modificar información, se comunica con la base de datos.

La base de datos procesa la operación y devuelve la información solicitada al backend. Luego, el backend procesa la respuesta y la envía nuevamente al frontend.

Finalmente, el frontend recibe la respuesta del backend y actualiza la interfaz para mostrar al usuario el resultado de la operación.

En resumen, el flujo de comunicación es:

Usuario → Frontend → Backend → Base de datos → Backend → Frontend → Usuario


# Características principales

La aplicación contará con diferentes características que permitirán a los usuarios utilizar el sistema de manera sencilla, rápida y organizada.

- **Interfaz web:** permite acceder a la aplicación desde un navegador sin necesidad de instalar software adicional.
- **Registro e inicio de sesión:** permite a los usuarios crear una cuenta e ingresar de forma segura a la aplicación.
- **Gestión de usuarios:** permite administrar la información correspondiente a cada usuario.
- **Navegación sencilla:** la aplicación contará con una interfaz clara e intuitiva para facilitar el acceso a sus diferentes secciones.
- **Gestión de información:** permite consultar, agregar, modificar y eliminar información según las funcionalidades disponibles.
- **Búsqueda y filtrado:** facilita la localización de información dentro de la aplicación.
- **Validación de datos:** verifica que la información ingresada por el usuario sea correcta antes de ser procesada.
- **Comunicación con el servidor:** el frontend se comunica con el backend mediante una API para procesar las diferentes acciones realizadas por los usuarios.
- **Persistencia de datos:** la información se almacena en una base de datos para poder conservarla y consultarla posteriormente.
- **Diseño responsive:** la interfaz se adapta a diferentes tamaños de pantalla y dispositivos.
- **Seguridad:** se implementan mecanismos de autenticación y autorización para proteger el acceso a las funcionalidades y datos de la aplicación.


# Documentación de la interfaz y navegación

## Interfaz de usuario

La interfaz de la aplicación web está diseñada para permitir que los usuarios puedan acceder a las diferentes funcionalidades de manera clara, rápida y sencilla.

Los elementos de la interfaz se encuentran organizados de forma que las acciones principales sean fácilmente identificables. Se busca mantener una estructura visual consistente en todas las secciones de la aplicación.

Entre los principales elementos de la interfaz se encuentran:

- **Barra de navegación:** permite acceder a las diferentes secciones de la aplicación.
- **Menú principal:** contiene las opciones disponibles para el usuario.
- **Botones de acción:** permiten realizar operaciones como crear, editar, eliminar, guardar o cancelar.
- **Formularios:** permiten ingresar y modificar información.
- **Tablas y listados:** muestran la información almacenada en el sistema.
- **Campos de búsqueda:** permiten localizar información específica.
- **Filtros:** permiten reducir los resultados mostrados según diferentes criterios.
- **Mensajes de estado:** informan al usuario si una operación fue realizada correctamente o si ocurrió algún error.
- **Elementos responsive:** permiten que la interfaz pueda adaptarse a diferentes tamaños de pantalla.

## Navegación

La navegación de la aplicación permite desplazarse entre las diferentes páginas y funcionalidades disponibles.

El usuario comienza en la página principal y, dependiendo de las opciones disponibles, puede acceder a las diferentes secciones del sistema.

Un ejemplo del recorrido general de navegación es:

Página de inicio
       │
       ├── Iniciar sesión
       │       │
       │       └── Panel principal
       │               │
       │               ├── Gestión de usuarios
       │               │
       │               ├── Gestión de información
       │               │
       │               ├── Búsqueda y filtros
       │               │
       │               └── Configuración
       │
       └── Registrarse
               │
               └── Crear cuenta


# Funcionamiento de la aplicación web

La aplicación web permite a los usuarios acceder a sus diferentes funcionalidades mediante un navegador.

El usuario interactúa con la interfaz y realiza acciones como registrarse, iniciar sesión, consultar información, realizar búsquedas y gestionar datos.

El frontend recibe las acciones del usuario y se comunica con el backend mediante una API. El backend procesa las solicitudes, valida los datos y se comunica con la base de datos cuando es necesario.

La información obtenida o modificada es enviada nuevamente al frontend, donde se muestra el resultado al usuario.

## Principales funciones

- Registro e inicio de sesión de usuarios.
- Consulta y gestión de información.
- Búsqueda y filtrado de datos.
- Validación de información ingresada.
- Comunicación entre frontend y backend mediante una API.
- Almacenamiento de información en una base de datos.
- Manejo de errores y mensajes al usuario.
- Cierre de sesión.

