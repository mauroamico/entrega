Este es un proyecto web en Django que implementa un sistema para gestionar información sobre tornillos, tuercas y arandelas. Utiliza el patrón MVT (Model-View-Template) de Django para organizar la estructura del proyecto.

## Funcionalidades

- Lista de Tornillos, Tuercas y Arandelas: Muestra una lista de cada tipo de elemento almacenado en la base de datos.
- Formularios de Inserción: Permite insertar nuevos tornillos, tuercas y arandelas en la base de datos.
- Búsqueda en la Base de Datos: Proporciona un formulario para buscar elementos en la base de datos.

## Estructura del Proyecto

- `myproject/`: Carpeta raíz del proyecto Django.
- `myapp/`: Aplicación principal del proyecto.
  - `models.py`: Define los modelos de la base de datos (Tornillo, Tuerca, Arandela).
  - `forms.py`: Define los formularios para inserción y búsqueda.
  - `views.py`: Contiene las vistas para mostrar listas, formularios y resultados de búsqueda.
  - `templates/`: Carpeta que contiene las plantillas HTML.
  - `urls.py`: Define las URLs para acceder a las vistas.
- `manage.py`: Script de administración de Django.
