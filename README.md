# Home About

Proyecto básico de Django para una página de inicio y una sección "About".

## Descripción

Este proyecto incluye:
- una vista principal en la ruta de inicio,
- una vista secundaria de "About",
- plantillas reutilizables con base HTML,
- navegación entre páginas mediante enlaces.

## Estructura principal

- `django_base/`: configuración del proyecto Django.
- `pages/`: aplicación con vistas, URLs y modelos.
- `templates/`: plantillas HTML del proyecto.
- `manage.py`: comando principal para ejecutar el proyecto.
- `db.sqlite3`: base de datos local del proyecto.

## Requisitos

- Python 3
- Django

## Instalación

1. Clona el repositorio.
2. Entra al proyecto.
3. Crea un entorno virtual (opcional pero recomendado):

```bash
python -m venv venv
source venv/bin/activate
```

4. Instala las dependencias:

```bash
pip install -r requirements.txt
```

## Ejecutar el proyecto

```bash
python manage.py runserver
```

Luego abre en el navegador:

```text
http://127.0.0.1:8000/
```

## Rutas principales

- Inicio: `/`
- About: `/about`

## Autor

Proyecto de ejemplo para practicar Django y templates.
