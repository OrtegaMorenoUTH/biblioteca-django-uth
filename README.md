Sistema de Biblioteca con Django

Descripción del proyecto: Este proyecto es un Sistema de Biblioteca desarrollado como práctica de la Unidad 1 de la materia Aplicaciones Web Orientadas a Servicios.  
Permite la gestión básica de libros mediante el uso del framework Django, aplicando conexión a base de datos y despliegue de una aplicación web.
El objetivo principal es comprender el funcionamiento de los servicios web, el manejo de rutas, vistas, modelos y el control de versiones utilizando GitHub.

Tecnologías utilizadas:
- Python 3.10+ o superior
- Django
- MySQL Server 8.0+ o superior
- HTML5
- CSS3
- Bootstrap
- Git y GitHub
- PythonAnywhere
- VS Code (editor recomendado)
- Navegador web moderno

Instrucciones de instalación:

1. Clonar el repositorio:

   git clone <URL-del-repositorio>

2. Acceder a la carpeta del proyecto:

   cd biblioteca_django

3. Crear un entorno virtual:

   python -m venv venv

4. Activar el entorno virtual:

   Windows:
   venv\Scripts\activate

   Linux / Mac:
   source venv/bin/activate

5. Instalar las dependencias:

   pip install -r requirements.txt

6. Configurar la base de datos MySQL en el archivo settings.py.

7. Ejecutar las migraciones:

   python manage.py makemigrations  
   python manage.py migrate

8. Crear un superusuario:

   python manage.py createsuperuser

9. Ejecutar el servidor:

   python manage.py runserver

10. Acceder desde el navegador:

   http://127.0.0.1:8000/  
   http://127.0.0.1:8000/admin/

Estructura del proyecto

biblioteca_django/
│
├── biblioteca_project/
│   ├── settings.py
│   ├── asgi.py
│   ├── urls.py
│   └── wsgi.py
│
├── libros/
│   ├── models.py
│   ├── admin.py
│   ├── apps.py
│   ├── views.py
│   ├── urls.py
│   └── test.py
│
├── templates/
│   ├── base/
│   │   └── base.html
│   │   
│   └── libros/
│       ├── busqueda_avanzada.html
│       ├── detalles_autor.html
│       ├── detalle_libro.html
│       ├── estadisticas.html
│       ├── inicio.html
│       ├── lista_autores.html
│       └── lista_libros.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   │   
│   └── js/
│       └── main.js
│   
├── manage.py
├── .gitignore
└── requirements.txt


Información del autor

Nombre: Iris Rocio Ortega Moreno  
Carrera: Desarrollo de Software Multiplataforma  
Universidad: Universidad Tecnológica de Hermosillo  
Materia: Aplicaciones Web Orientadas a Servicios  
Profesor: Bernardo Prado Diaz

Proyecto elaborado como evaluacion de la Unidad 1.
