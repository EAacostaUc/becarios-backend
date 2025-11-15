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
│── becarios/                # App principal
│   ├── models.py            # Modelos
│   ├── serializers.py       # Serializadores
│   ├── views.py             # Vistas / API
│   └── urls.py
│
│── consulta_becarios/       # Proyecto Django
│   ├── settings.py
│   ├── urls.py
│   └── wsgi.py
│
│── becal_sqlite.db          # Base de datos
│── manage.py
