# Temario-de-Aplicaciones-Web


# ------------------------------------------------------------------
## 1.-Introducción al desarrollo web

![Uploading image.png…]()

### Historia y evolución del desarrollo web.
### El desarrollo web comenzó con la invención de la World Wide Web por Tim Berners-Lee en 1989, lanzando el primer sitio web en 1991 y el lenguaje HTML. La Web 1.0 (aproximadamente 1991-2003) fue estática, y la evolución se impulsó con la llegada de CSS para el diseño, la popularización de los motores de búsqueda como ALIWEB, y la introducción de imágenes y tablas. La Web 2.0 (desde 2003) se centró en la interactividad, la colaboración y el contenido generado por el usuario, con la incorporación de audio, video y animaciones. La Web 3.0 (actualidad y futuro) introduce la inteligencia artificial, la personalización y la semántica, y la Web 4.0 se perfila como una "red inteligente" con mayor interacción entre humanos y máquinas.

### Tipos de aplicaciones web (estáticas, dinámicas, SPA, PWA)
### Los tipos de aplicaciones web incluyen estáticas, de contenido fijo; dinámicas, que se actualizan constantemente con datos de bases de datos; de una sola página (SPA), que cargan una página y actualizan contenido dinámicamente para una experiencia más fluida; aplicaciones web progresivas (PWA), que ofrecen características similares a las aplicaciones móviles e incluso funcionan sin conexión; portales, que ofrecen acceso a diversas secciones como foros o correos; aplicaciones de comercio electrónico, diseñadas para tiendas online con pasarelas de pago; y aplicaciones basadas en gestores de contenidos (CMS), que facilitan la publicación y administración de contenido. 





## 2.Arquitectura de aplicaciones web

### Arquitectura Cliente-Servidor
### La arquitectura Cliente-Servidor es un modelo de diseño de software donde el cliente solicita recursos o servicios y el servidor responde, generalmente enviando datos o procesando acciones.


### Arquitectura de tres capas (presentación, lógica, datos)
### La arquitectura de tres capas estructura una aplicación en tres partes independientes:
### Presentación: Interfaz de usuario.
### Lógica: Procesamiento de información y reglas de negocio.
### Datos: Almacenamiento y gestión de datos.


### REST y API-first design
### REST (Representational State Transfer) es un estilo de arquitectura para diseñar servicios web que utiliza métodos HTTP para interactuar con recursos representados como URLs.
### El diseño API-first es una metodología donde el desarrollo de la API es el primer paso al crear una aplicación, definiendo y documentando la API antes de implementar la lógica y el frontend.






## 3. -Lenguajes y tecnologías fundamentales
### HTML, CSS, JavaScript, PHP, MySQL
### HTML, CSS, JavaScript, PHP y MySQL son lenguajes y tecnologías fundamentales para el desarrollo web. 
### HTML es un lenguaje de marcado utilizado para estructurar el contenido de las páginas web. CSS es un lenguaje de estilos usado para definir la presentación visual y el diseño de las páginas web. JavaScript es un lenguaje de programación que permite agregar interactividad y dinamismo a las páginas web en el lado del cliente. PHP es un lenguaje de programación del lado del servidor utilizado para desarrollar aplicaciones web dinámicas y gestionar la lógica de negocio. MySQL es un sistema de gestión de bases de datos relacional que se utiliza para almacenar y administrar datos en aplicaciones web.




## 4.-Control de versiones
### Git y GitHub
### Flujo de trabajo con ramas (branching, merge, pull requests)
### Git y GitHub son herramientas fundamentales para el control de versiones en el desarrollo de software. Git es un sistema de control de versiones distribuido que permite registrar y gestionar los cambios realizados en el código fuente. GitHub es una plataforma basada en Git que facilita la colaboración y el alojamiento de repositorios en línea. El flujo de trabajo con ramas implica crear ramas para desarrollar nuevas funcionalidades o corregir errores de forma aislada, realizar merges para integrar los cambios en la rama principal y utilizar pull requests para revisar y aprobar las modificaciones antes de su incorporación definitiva.



# ----------------------------------------------------------------------------

# Propósito de Aprendizaje 2: Desarrollar componentes y funcionalidades de una aplicación web
## 1.- Diseño e implementación del frontend
### Maquetación, wireframe y mockup son técnicas para planificar y representar visualmente la estructura y diseño de una interfaz web antes de su desarrollo. Una API (Interfaz de Programación de Aplicaciones) es un conjunto de reglas y definiciones que permite la comunicación entre el frontend y otros servicios o el backend.


## 2.- Diseño e implementación del backend
### El servidor es el componente responsable de ejecutar la lógica de la aplicación web, gestionar las operaciones solicitadas por los clientes y mantener la seguridad y estabilidad del sistema. El manejo de peticiones y respuestas HTTP implica recibir solicitudes desde el frontend o de otros servicios, procesarlas según la lógica de negocio y devolver respuestas apropiadas utilizando el protocolo HTTP, lo que permite la comunicación entre diferentes partes de la aplicación.
### La conexión a bases de datos, como MySQL, PostgreSQL o MongoDB, permite al backend almacenar, consultar, actualizar y eliminar información de manera eficiente y estructurada. Dependiendo del tipo de base de datos, se pueden manejar datos relacionales (tablas y relaciones en MySQL o PostgreSQL) o datos no relacionales (documentos en MongoDB), adaptándose a las necesidades específicas de la aplicación y facilitando la escalabilidad y el rendimiento.


## 3.- Bases de datos
### El modelado de datos y relaciones consiste en definir la estructura de las tablas y cómo se relacionan entre sí. Un ORM (Object Relational Mapping) es una herramienta que permite interactuar con bases de datos mediante objetos en el lenguaje de programación, facilitando la manipulación de datos. CRUD (Create, Read, Update, Delete) son las operaciones básicas para gestionar información desde el backend.


## 4.- Seguridad básica en aplicaciones web
### La validación de formularios consiste en comprobar que los datos introducidos por el usuario cumplen con los requisitos establecidos, previniendo errores y posibles vulnerabilidades como la inyección de código malicioso.
### La autenticación es el proceso mediante el cual se verifica la identidad de los usuarios, generalmente mediante credenciales como usuario y contraseña, y puede incluir mecanismos adicionales como autenticación de dos factores.
### La autorización determina los permisos y el nivel de acceso que tiene cada usuario dentro de la aplicación, asegurando que solo puedan realizar acciones o acceder a recursos para los que están habilitados.
### Estas prácticas básicas de seguridad son esenciales para proteger la información, prevenir accesos no autorizados y garantizar el correcto funcionamiento de una aplicación web.




# ----------------------------------------------------------------------------
# Propósito de Aprendizaje 3: Implementar y desplegar una aplicación web funcional


## 1.- Integración de frontend y backend
### La interfaz de usuario frontend es la parte visual y funcional de la aplicación que interactúa directamente con el usuario, construida usualmente con tecnologías como HTML, CSS y JavaScript. El manejo de API implica la utilización de interfaces de programación para que el frontend se comunique con el backend, enviando y recibiendo datos de manera estructurada mediante protocolos como HTTP. El proceso de solicitud y respuesta de backend consiste en recibir peticiones desde el frontend, procesar la lógica de negocio y devolver respuestas apropiadas, facilitando la interacción entre usuario y servidor.

## 2.- Almacenamiento en servidor
### Los tipos de servidores pueden incluir servidores físicos, virtuales o en la nube, donde se alojan y procesan las aplicaciones web. Los servidores y servicios de hosting son plataformas que ofrecen infraestructura para desplegar y mantener aplicaciones web accesibles desde Internet, incluyendo opciones como hosting compartido, VPS, servidores dedicados y servicios cloud. Los proveedores de servicios de almacenamiento ofrecen soluciones para guardar archivos, bases de datos y otros recursos, facilitando la escalabilidad y seguridad de la información en aplicaciones web.

## 3.- Optimización y rendimiento
### La optimización de recursos consiste en mejorar el uso de imágenes, scripts y otros elementos para reducir tiempos de carga y mejorar la experiencia del usuario, utilizando técnicas como compresión, minificación y carga diferida. El despliegue de aplicaciones web es el proceso de publicar y distribuir la aplicación en servidores o plataformas para que esté disponible a los usuarios finales. CI/CD básico (Integración y Entrega Continua) se refiere a la automatización de pruebas, integración y despliegue de código, permitiendo actualizaciones rápidas y seguras. La documentación del proyecto es la creación de materiales que explican la arquitectura, uso y mantenimiento de la aplicación, facilitando la colaboración y el soporte técnico.

