# 🧩 Tasktris

**Tasktris** es una aplicación de gestión de tareas visualmente inspirada en Tetris, donde cada tarea se representa como una "pieza" en una cuadrícula. El objetivo es ofrecer una experiencia de planificación atractiva, ordenada y flexible.

Este proyecto forma parte de una ruta de aprendizaje para dominar desarrollo web moderno con .NET, arquitectura limpia, buenas prácticas, testing y más adelante Angular en el frontend.

---

## 🚀 Tecnologías utilizadas

### Backend
- [.NET 8](https://dotnet.microsoft.com/en-us/download) – Framework principal
- **ASP.NET Core Web API** – Para construir APIs RESTful
- **Entity Framework Core** – ORM para acceso a base de datos
- **FluentValidation** – Validación de entrada
- **AutoMapper** – Mapeo de entidades y DTOs
- **JWT** – Autenticación basada en tokens
- **xUnit** – Testing
- **Swagger / Swashbuckle** – Documentación interactiva

### Arquitectura
- Clean Architecture (por capas): `Domain`, `Application`, `Infrastructure`, `API`
- Principios SOLID
- Repositorios y servicios

### Futuro (Frontend)
- Angular – SPA para consumir la API y visualizar tareas como piezas de Tetris

---

## 📌 Estado actual

✅ Proyecto inicial creado  
✅ API ejecutándose con Swagger  
✅ Estructura Clean Architecture en construcción  
🔜 Modelado de entidades y persistencia con EF Core  
🔜 Endpoints para gestión de tareas  
🔜 Seguridad JWT y autenticación de usuarios

---

## ⚙️ Cómo ejecutar el proyecto

> Requisitos previos:
> - .NET 8 SDK
> - Visual Studio 2022+ o VS Code
> - SQL Server (local o Docker) o SQLite (según configuración futura)

### 1. Clonar el repositorio

```bash
git clone https://github.com/tu-usuario/tasktris.git
cd tasktris

### 2. Restaurar y compilar
dotnet restore
dotnet build

### 3. Ejecutar el proyecto
cd Tasktris.API
dotnet run

### 4. Verificar API
Accede a Swagger:
http://localhost:5139/swagger
(o el puerto configurado en launchSettings.json)