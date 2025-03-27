# 📦 Aplicación Spring Boot - API de Productos
🚀 Proyecto de una API REST en **Spring Boot** con base de datos **H2** y pruebas automatizadas con **JUnit y Mockito**.
## 📜 Descripción
Esta aplicación es una API REST para gestionar productos. Permite realizar operaciones **CRUD** (Crear, Leer, Actualizar y Eliminar) sobre productos mediante endpoints HTTP.
## 🛠 Tecnologías Usadas
- ✅ **Java 17+**
- ✅ **Spring Boot**
- ✅ **Maven**
- ✅ **H2 Database**
- ✅ **Spring Data JPA**
- ✅ **JUnit 5 y Mockito** (Pruebas automatizadas)
---
## 📂 Estructura del Proyecto
mi-app/ ├── src/main/java/com/example/app/ # Código principal │ ├── AppApplication.java # Clase principal │ ├── controller/ # Controlador REST │ │ ├── ProductController.java │ ├── service/ # Lógica de negocio │ │ ├── ProductService.java │ ├── repository/ # Acceso a base de datos │ │ ├── ProductRepository.java │ ├── model/ # Entidad Producto │ │ ├── Product.java ├── src/main/resources/ # Recursos del proyecto │ ├── application.properties # Configuración de la base de datos H2 ├── src/test/java/com/example/app/ # Código de pruebas │ ├── controller/ │ │ ├── ProductControllerTest.java │ ├── service/ │ │ ├── ProductServiceTest.java ├── pom.xml # Archivo de configuración de Maven ├── README.md # Este archivo
---
## 📌 Instalación y Configuración
### 🔹 **Requisitos Previos**
Asegúrate de tener instalado en tu sistema:
- Java 17+ ([Descargar JDK](https://adoptium.net/))
- Maven ([Descargar Maven](https://maven.apache.org/download.cgi))
- Visual Studio Code ([Descargar VS Code](https://code.visualstudio.com/))
### 🔹 **Clonar el Repositorio**
```sh
git clone https://github.com/tuusuario/mi-app.git
cd mi-app
🔹 Ejecutar la Aplicación
1.	Abrir la terminal y ejecutar:
2.	mvn spring-boot:run
3.	Abrir el navegador y probar la API:
4.	http://localhost:8080/api/products
🚀 Endpoints de la API
Método	Endpoint	Descripción
GET	/api/products	Obtiene todos los productos
POST	/api/products	Crea un nuevo producto
PUT	/api/products/{id}	Actualiza un producto por ID
DELETE	/api/products/{id}	Elimina un producto por ID
Ejemplo de JSON para POST /api/products:
{
  "name": "Laptop",
  "price": 1200.00
}

🧪 Ejecutar Pruebas Automatizadas
Para ejecutar las pruebas unitarias con JUnit y Mockito, usa el siguiente comando:
mvn test
📜 Licencia
Este proyecto está bajo la licencia MIT.
🚀 ¡Gracias por visitar este repositorio! 😃
Si te gustó el proyecto, ¡dale una estrella ⭐ en GitHub!
