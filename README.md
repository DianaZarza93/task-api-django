# 🧠 Task API - Django REST

API RESTful para gestión de tareas desarrollada con Django REST Framework.  
Incluye autenticación por token, documentación interactiva con Swagger y operaciones CRUD completas.

---

## 🚀 Features

- Crear, listar, actualizar y eliminar tareas (CRUD)
- Autenticación de usuarios con token
- Endpoints protegidos
- Documentación interactiva con Swagger
- Estructura profesional de API REST

---

## 🛠️ Tecnologías

- Python
- Django
- Django REST Framework
- Token Authentication
- Swagger (drf-yasg)

---

## 🔐 Autenticación

La API utiliza autenticación por token.

### Obtener token:

POST `/api/token/`

```json
{
  "username": "tu_usuario",
  "password": "tu_password"
}