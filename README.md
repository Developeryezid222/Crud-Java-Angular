# Fullstack
# 🧑‍💼 Plataforma de Gestión de Clientes (CMS) - Stack Full Stack Robusto

Aplicación web Full Stack completa diseñada para la gestión eficiente del ciclo de vida de los usuarios (CRUD). Este proyecto demuestra la capacidad de integración y desarrollo de punta a punta, adhiriéndose a patrones de diseño de software y buenas prácticas de seguridad.

La solución combina la eficiencia del Backend Java/Spring Boot con la reactividad y la modernidad de Angular 19

- **Frontend:** Angular 19
- **Backend:** Spring Boot (Java 17)
- **Base de datos:** MySQL (modelada y gestionada con MySQL Workbench)

---

## 🎯 Objetivo

El objetivo de esta aplicación es permitir la administración de usuarios a través de un sistema CRUD (Crear, Leer, Actualizar, Eliminar), proporcionando una interfaz amigable y funcionalidades robustas para gestionar la información de manera eficiente.

---

## ⚙️ Tecnologías Utilizadas

### 🧩 Frontend

- Angular 19 con TypeScript
- Formularios Reactivos (`ReactiveForms`)
- Bootstrap para el diseño visual
- Angular Material (opcional, si está integrado)
- Interceptores HTTP para manejo global de errores y autenticación

### 🧪 Backend

- Spring Boot con Java 17+
- Controladores REST (`@RestController`)
- Servicios y Repositorios (`@Service`, `@Repository`)
- Manejo de peticiones HTTP (`GET`, `POST`, `PUT`, `DELETE`)
- Configuración de CORS

### 🛢️ Base de Datos

- MySQL como sistema gestor de base de datos
- Modelado de tablas desde MySQL Workbench
- Conexión mediante `spring.datasource` en `application.properties`

---

## ✨ Funcionalidades

- ✔️ Listado de usuarios
- ➕ Creación de nuevos usuarios
- ✏️ Edición de usuarios existentes
- ❌ Eliminación de usuarios
- 🔍 Validaciones en los formularios (campos obligatorios, correos válidos, etc.)
- ⚠️ Manejo de errores del servidor
- 🔐 Soporte para integración de autenticación (extensible)

---

## 🧪 Ejecución del Proyecto

### 🖥️ Backend

1. Clonar el repositorio del backend.
2. Configurar `application.properties` con tu conexión MySQL.
3. Ejecutar el proyecto con Spring Boot (desde IDE o línea de comandos).
4. Asegurarse que esté disponible en: `http://localhost:8081/api/users` (ejemplo).

### 🌐 Frontend

1. Clonar el repositorio del frontend.
2. Instalar dependencias: `npm install`
3. Ejecutar: `ng serve`
4. Acceder a: `http://localhost:4200`

---

## 📸 Capturas (Opcional)



---

## 📦 Estructura de Carpetas
<h4 align="left">├── client-app/              # Proyecto Frontend (Angular)<br>│   ├── src/app/components/  # Componentes reutilizables<br>│   ├── src/app/services/    # Lógica de comunicación con el Backend<br>│   └── src/app/models/      # Interfaces TypeScript<br>├── server-api/              # Proyecto Backend (Spring Boot)<br>│   ├── src/main/java/controller/ # Controladores REST<br>│   ├── src/main/java/service/    # Lógica de Negocio (Servicios)<br>│   └── src/main/java/repository/ # Persistencia (Spring Data JPA)<br>└── README.md</h4>

###


<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" height="40" alt="typescript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" height="40" alt="java logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" height="40" alt="javascript logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original-wordmark.svg" height="40" alt="tailwindcss logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" height="40" alt="spring logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" height="40" alt="mysql logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" height="40" alt="angularjs logo"  />
</div>

###
