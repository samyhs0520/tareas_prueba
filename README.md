# Proyecto Full Stack: Spring Boot & Angular

Este repositorio contiene dos proyectos:
- **Backend**: Implementado en Spring Boot.
- **Frontend**: Implementado en Angular.

## Requisitos previos
Asegúrate de tener instalados los siguientes requisitos antes de ejecutar los proyectos:

- **Java 17** o superior
- **Maven**
- **Node.js** y **npm**
- **Angular CLI**
- **Base de datos H2**

---

## Configuración y Ejecución

Clone el repositorio el cual contiene el frontend y al backend 
git clone https://github.com/samyhs0520/tareas_prueba.git

### 1. Ejecutar el Backend (Spring Boot)

1. Clona el repositorio:
   cd tareas_prueba/crud_tarea
   ```
2. Configura la base de datos en `application.properties` o cambia el nombre del archivo  `application.properties.example` a  `application.properties`
3. Compila y ejecuta el proyecto con Maven:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```
4. El backend estará disponible en: `http://localhost:8080`

---

### 2. Ejecutar el Frontend (Angular)

1. Accede al directorio del frontend:
   ```bash
   cd ../front_tarea
   ```
2. Instala las dependencias:
   ```bash
   npm install
   ```
3. Ejecuta el servidor de desarrollo:
   ```bash
   ng serve
   ```
4. El frontend estará disponible en: `http://localhost:4200`




