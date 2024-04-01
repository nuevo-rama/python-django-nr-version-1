# python-django-nr-version-1
Web Site with Python / Django

- Para Desarrollo

1. Terminal:

```bash
git clone
```

2. Crear un entorno virtual

`pip install virtualenv`

3. Nombramos la configuracion del entorno virtual

`python3 -m virtualenv venv`

4. Para correr el entorno virtual:

`cd venv/bin/source activate`

5. Volver al directorio del entorno virtual

`cd ..`
`cd ..`

6. Instalamos Django

`pip install django`

7. Inicializar el proyecto de Django

`django-admin startproject django_blog_v1 .` 

" ." sirve para crear las carpetas dentro del proyecto

8. Crear en la base de datos las tablas
`cd django_blog_v1`
`python manage.py migrate`

9. Arrancamos el servidor

`python manage.py runserver`






