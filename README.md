# Blog Django Completo Total 📲 📝 💻

## Proyecto fullstack realizado con Python 3.10.6 y Django 4.1.2.

Este proyecto es un blog completamente funcional y probado. Sé exactamente cómo funciona cada parte y cómo interactúan los componentes. Está desarrollado con las mejores prácticas y tecnologías modernas.

## Funcionalidades:

- [x] Registro  
- [x] Login  
- [x] Logout  
- [x] Editar Usuario  
- [x] Redactar posteos  
- [x] Subir imagen al crear posteo  
- [x] Editar posteos  
- [x] Borrar posteos  
- [x] Buscar posteos por título  
- [x] Paginado de posteos  

## Construído con:  
- [x] Python 3.10.6  
- [x] Django 4.1.2  
- [x] SQLite  
- [x] HTML 5  
- [x] CSS clásico y Tailwind CSS  
- [x] Javascript  
- [x] GIT  
- [x] Íconos: https://fontawesome.com/ , https://materialdesignicons.com/


### Instalación - Linux

- Crear y activar un entorno virtual (opcional pero recomendado):

python3 -m venv venv
source venv/bin/activate

- Instalar dependencias:

pip install -r requirements.txt

- Aplicar migraciones (usa SQLite):

python manage.py migrate

- Levantar el servidor:

python3 manage.py runserver

#### Generar mock con datos iniciales

python manage.py shell < seed_data.py