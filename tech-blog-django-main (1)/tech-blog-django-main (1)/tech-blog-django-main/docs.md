Blog Django Completo Total 📲 📝 💻
Proyecto fullstack realizado con Python 3.10.6 y Django 4.1.2.
Este proyecto es un blog completamente funcional y probado. Sé exactamente cómo funciona cada parte y cómo interactúan los componentes. Está desarrollado con las mejores prácticas y tecnologías modernas.

Funcionalidades:
 Registro
 Login
 Logout
 Editar Usuario
 Redactar posteos
 Subir imagen al crear posteo
 Editar posteos
 Borrar posteos
 Buscar posteos por título
 Paginado de posteos
Construído con:
 Python 3.10.6
 Django 4.1.2
 SQLite
 HTML 5
 CSS clásico y Tailwind CSS
 Javascript
 GIT
 Íconos: https://fontawesome.com/ , https://materialdesignicons.com/
Instalación - Linux
Crear y activar un entorno virtual (opcional pero recomendado):
python3 -m venv venv source venv/bin/activate

Instalar dependencias:
pip install -r requirements.txt

Aplicar migraciones (usa SQLite):
python manage.py migrate

Levantar el servidor:
python3 manage.py runserver

Generar mock con datos iniciales
python manage.py shell < seed_data.py