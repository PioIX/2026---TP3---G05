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