# Reto 9: Desarrollo de Aplicación Web y Conexión a Base de Datos

Crear una aplicación simple que se conecte a una base de datos, ya sea mediante un sistema local o un servicio en la nube (como Amazon RDS, Google Cloud SQL o Azure SQL Database), demostrando operaciones básicas de lectura y escritura, ademas debe permitir la modificación del campo y su eliminación.


## ¿Qué son las operaciones CRUD?
Las operaciones **CRUD** son un acrónimo en inglés que define las cuatro funciones básicas de persistencia en bases de datos: **Create** (Crear), 
**Read** (Leer/Consultar), 
**Update** (Actualizar) y 
**Delete** (Borrar/Eliminar). 
En resumen, permiten gestionar de forma completa la información guardada en cualquier sistema de datos.

---

---

## Planteamiento del Reto

### 1. Selecciona las Tecnologías
* **Lenguajes y Frameworks:** Python con Flask o Django, JavaScript con Node.js y Express o Ruby.
* **Base de datos:** Elegir entre un sistema de gestión local o un servicio en la nube que se adapte a los objetivos del proyecto.


### 2. Diseña la Aplicación Web
* Planificar el diseño definiendo las funcionalidades básicas para interactuar con los datos (añadir, visualizar, modificar y eliminar registros).
* Posibilidad de utilizar inteligencia artificial para mejorar la experiencia del usuario o automatizar procesos.

### 3. Configura la Base de Datos
* Configurar el entorno local o en la nube asegurando su accesibilidad.
* Creación de la base de datos, las tablas necesarias y los parámetros de conexión.

### 4. Desarrolla la Aplicación Web
* Implementar operaciones básicas de lectura y escritura utilizando el stack tecnológico elegido.
* Gestionar adecuadamente las conexiones, el manejo de errores y la seguridad en la nube.

### 5. Integra y Prueba
* Realizar pruebas para asegurar el correcto funcionamiento de las operaciones descritas.
* Comprobar la seguridad y escalabilidad, apoyándose opcionalmente en la inteligencia artificial.
---

---

## Problemas Encontrados en el Desarrollo

Durante la práctica y el despliegue del proyecto en la nube (utilizando el servidor Flask en el **puerto 5000**), se registraron las siguientes incidencias técnicas destacadas:

* **Problemas de acceso inicial a la nube y AWS:** Hubo dificultades para establecer la conexión con el servidor en los primeros intentos. Como solución alternativa para forzar la apertura del puerto y canalizar el flujo de datos hacia AWS, se recurrió a estructurar la entrada completa del programa mediante un marcador de fin de archivo (**EOF** / *End of File*), permitiendo que el sistema procesara el bloque de código de golpe.
* **Errores de alineación y compilación en la consola:** El código presentado en la terminal sufría de desalineaciones y caracteres indeseados que impedían la correcta compilación. Se solventó aplicando comandos específicos de limpieza y posicionamiento para reubicar las líneas de código al inicio y eliminar los fallos de sintaxis que bloqueaban la ejecución.

