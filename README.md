# 🚀 Nombre del Proyecto
**Sistema de Recuperación de Horas Médicas - RedSalud**

> Proyecto fullstack para la gestión de solicitudes de recuperación de horas médicas, con panel de administración, autenticación de usuarios y notificación por correo.

---

## 📌 Descripción

Este sistema permite a los usuarios recuperar o reagendar horas médicas de forma ágil, conectándose con el área administrativa de RedSalud.  
Incluye:
- **Frontend**: SPA en React + Vite.
- **Backend**: API REST con Django.
- **Base de datos**: SQLite (en desarrollo, adaptable a PostgreSQL/MySQL).

---

## ⚙️ Tecnologías

- **Frontend**: React, Vite, JavaScript, Axios.
- **Backend**: Django, Django REST Framework.
- **Base de datos**: SQLite.
- **Otros**: Git, VSCode, Postman.

---

## 🗂️ Estructura del Proyecto
    proyecto/
    ├── back-end/
    │ ├── manage.py
    │ ├── requirements.txt
    │ ├── Apps/
    │ ├── forms/ # App para formularios médicos
    │ ├── tasks/ # App para tareas
    │ ├── user/ # App para gestión de usuarios
    │ ├── email_service/ # App para notificaciones por correo
    │ └── misitio/ # Configuración principal del sitio Django
    ├── front-end/
    │ ├── src/
    │ ├── public/
    │ ├── package.json
    │ ├── vite.config.js
    │ └── README.md
    └── Documentacion/
    ├── Manual sistema.docx
    ├── Plan de Pruebas para RedSalud.docx
    └── Documentación de usuario.pdf


---
### 🚀 Instalación y Ejecución

  ## 1️⃣ Clonar repositorio
    git clone <https://github.com/Synosuree/RedSalud.git>
    cd proyecto
    cd back-end

  ## 2️⃣ Backend - Django
  # Crear entorno virtual
      python -m venv venv
    
  # Activar entorno
      # Windows:
      venv\Scripts\activate
      
      # Linux/macOS:
      source venv/bin/activate
  
  # Instalar dependencias
    pip install -r requirements.txt
  
  # Migraciones
    python manage.py migrate
  
  # Ejecutar servidor
    python manage.py runserver

### 3️⃣ Frontend - React

    cd front-end
  
  # Instalar dependencias
    npm install
  
  # Ejecutar servidor de desarrollo
    npm run dev

### 📄 Documentación
   # Manual de usuario
   # Plan de pruebas

 👥 Autores
  - Diego Robles 
  - Javier González
  - Sebastián Hidalgo
  - Matias Rietta
  - Matias Sepúlveda

### 📄 Licencia
    Este proyecto es de uso interno para RedSalud.
    Todos los derechos reservados © 2025.


