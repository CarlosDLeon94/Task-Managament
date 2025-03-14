# Task Management API

## 📌 Descripción
Esta API RESTful permite gestionar una lista de tareas (To-Do List), proporcionando endpoints para crear, leer, actualizar y eliminar tareas.

## 🚀 Tecnologías Utilizadas
- **Java 17**
- **Spring Boot** (Spring Web, Spring Data JPA, H2 Database)
- **Swagger/OpenAPI** (para documentación de la API)
- **Git & GitHub** (para control de versiones)
- **Postman** (para pruebas de API)

## 📂 Estructura del Proyecto
```
Task-Managament/
│── src/
│   ├── main/
│   │   ├── java/com/examen/api/
│   │   │   ├── controller/
│   │   │   ├── entity/
│   │   │   ├── excepciones/
│   │   │   ├── repository/
│   │   │   ├── sw/
│   │   │   ├── ApiApplication.java
│   │   ├── resources/
│   │       ├── application.properties
│── pom.xml
│── README.md
```

## 🔥 Instalación y Ejecución
1. Clonar el repositorio:
   ```bash
   git clone https://github.com/CarlosDLeon94/Task-Managament.git
   cd Task-Managament
   ```
2. Compilar y ejecutar el proyecto con Maven:
   ```bash
   mvn spring-boot:run
   ```
3. Acceder a la documentación Swagger en:
   ```
   http://localhost:8080/swagger-ui.html
   ```

## 📌 Endpoints Disponibles
| Método | Endpoint           | Descripción |
|--------|-------------------|-------------|
| POST   | `/api/tasks`       | Crear una nueva tarea |
| GET    | `/api/tasks`       | Obtener todas las tareas |
| GET    | `/api/tasks/{id}`  | Obtener una tarea por ID |
| PUT    | `/api/tasks/{id}`  | Actualizar una tarea |
| DELETE | `/api/tasks/{id}`  | Eliminar una tarea |

## 🛠️ Configuración de Git y GitHub
1. Crear un repositorio en **GitLab** o **GitHub**.
2. Crear dos ramas:
   ```bash
   git checkout -b feature/task-management
   ```
3. Realizar commits descriptivos en la rama `feature/task-management`.
4. Crear un **Merge Request (MR)** en GitLab desde `feature/task-management` a `main`.
5. Resolver un conflicto en el MR si es necesario.

## 🧪 Pruebas con Postman
1. Crear una colección en **Postman** con los siguientes tests:
   - Crear una tarea.
   - Obtener todas las tareas.
   - Obtener una tarea por ID.
   - Actualizar una tarea.
   - Eliminar una tarea.
2. Agregar **pruebas automatizadas** en Postman para verificar:
   - El código de respuesta HTTP.
   - Que el título de la tarea no esté vacío.
3. Exportar la colección de Postman y adjuntarla en el repositorio.

## 📜 Evaluación
### Criterios de Evaluación
✅ Implementación correcta de la API con Java 17 y Spring Boot.
✅ Uso de buenas prácticas (DTOs, validaciones, manejo de excepciones).
✅ Documentación de la API con Swagger/OpenAPI.
✅ Correcta configuración de Git y GitHub.
✅ Correcta implementación de pruebas en Postman.

## 📎 Entrega
1. Subir el proyecto a un repositorio en **GitLab**.
2. Incluir un archivo `README.md` con:
   - Instrucciones para ejecutar la aplicación.
   - Instrucciones para ejecutar las pruebas en Postman.
   - Capturas de pantalla de la API documentada en Swagger/OpenAPI y de las pruebas en Postman.
3. Enviar el enlace del repositorio al evaluador.

---
Si necesitas más ajustes en el README, dime y lo modificamos. 🚀

