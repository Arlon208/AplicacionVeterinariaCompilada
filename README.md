
🏛️ Arquitectura del Sistema
La aplicación está construida sobre un modelo de arquitectura de tres capas, que separa la funcionalidad en niveles lógicos bien definidos. Esto mejora la claridad del código, la reutilización y la facilidad de mantenimiento.

Capa de Presentación (Front-End):
Esta capa es la interfaz de usuario que se ejecuta en el navegador. Construida con HTML, CSS, y JavaScript, se encarga de mostrar la información al usuario y de enviar solicitudes a la API del back-end.

Capa de Lógica de Negocio (Back-End):
Este es el núcleo de la aplicación. Desarrollado con Java y Spring Boot, recibe y procesa todas las solicitudes del front-end. Esta capa contiene la lógica de negocio (por ejemplo, validación de datos) y coordina la interacción con la base de datos.

Capa de Acceso a Datos (Persistencia):
Esta capa se comunica directamente con la base de datos. Utiliza Spring Data JPA para realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) en la base de datos MySQL, asegurando una gestión eficiente de la información.

⚙️ Tecnologías Utilizadas
Categoría	Tecnología	Descripción
Front-End	HTML5, CSS3, JavaScript	Tecnologías estándar para la creación de la interfaz de usuario.
Back-End	Java (JDK 21), Spring Boot, Maven	Framework líder para el desarrollo de APIs. Maven se usa para la gestión de dependencias y la construcción del proyecto.
Base de Datos	MySQL	Base de datos relacional para el almacenamiento persistente de los datos.

📋 Requisitos del Sistema
Para ejecutar la aplicación, se requiere el siguiente entorno:

Java Development Kit (JDK) 21: La aplicación está compilada para esta versión.

Servidor MySQL: Una instancia de MySQL en ejecución (local o remota).

Maven: Para la construcción y gestión de dependencias del proyecto.

Ejecutar la Aplicación:

Ejecute el archivo iniciar_app.bat
La aplicación se iniciará en http://localhost:8080.

Acceso al Sistema:

Abra su navegador web y navegue a la URL http://localhost:8080 para acceder a la interfaz de usuario del sistema.
