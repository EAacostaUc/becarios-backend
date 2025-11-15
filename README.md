# 🧾 Becarios Backend

Este es el **backend del sistema de consulta de becarios**, desarrollado para el Trabajo Práctico de Lenguaje de Programación 3 (LP3), 2° semestre 2025.

El objetivo de este backend es permitir la consulta de datos de becarios del programa BECAL utilizando una base de datos en formato SQLite (`becal_sqlite.db`).

---

## 🛠️ Tecnologías utilizadas

- Python 3.14.0 
- Django  
- Django REST Framework  
- SQLite  

---

## 📁 Estructura del proyecto

backend/
├── becarios/ # 📌 App principal del proyecto (lógica del backend)
│ ├── pycache/ # Archivos compilados automáticamente por Python
│ ├── migrations/ # Migraciones de la base de datos
│ ├── init.py # Indica que es un paquete de Python
│ ├── admin.py # Configuración del panel de administración
│ ├── apps.py # Configuración de la app 'becarios'
│ ├── models.py # Modelos ORM (representan tablas)
│ ├── serializers.py # Serializadores para API REST
│ ├── tests.py # Tests automatizados
│ └── views.py # Vistas / Endpoints de la API
│
├── consulta_becarios/ # 📌 Proyecto Django principal
│ ├── pycache/
│ ├── init.py
│ ├── asgi.py # Configuración para servidores ASGI
│ ├── settings.py # Configuración global del proyecto
│ ├── urls.py # Rutas principales del proyecto
│ └── wsgi.py # Configuración para servidores WSGI
│
├── venv/ # Entorno virtual de Python
│
├── becal_sqlite.db # Base de datos SQLite utilizada
│
└── manage.py # Script principal para ejecutar comandos Django
