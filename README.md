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

### 1. Ejecutar el Backend (Spring Boot)

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu-repo.git
   cd tu-repo/backend
   ```
2. Configura la base de datos en `application.properties` o `application.yml`.
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
   cd ../frontend
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

---

## Variables de Entorno
Puedes definir variables de entorno para configurar la conexión entre el backend y el frontend.

Ejemplo para configurar el **backend en el frontend** (en `environment.ts`):
```ts
export const environment = {
  production: false,
  apiUrl: 'http://localhost:8080/api'
};
```

---

## Contacto
Si tienes preguntas o problemas, abre un issue en este repositorio o contáctame.

