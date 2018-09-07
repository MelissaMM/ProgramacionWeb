# ProgramacionWeb
1. Dibuje un arbol con la estructura basica de un proyecto y una aplicación de Django:
Django
//Proyecto
├── mysite
|       __init__.py
|       settings.py
|       urls.py
|       wsgi.py
├── manage.py

//App Django
└── blog
    ├── migrations
    |       __init__.py
    ├── __init__.py
    ├── admin.py
    ├── models.py
    ├── tests.py
    └── views.py

2. Mencione tres argumentos que gestiona el comando manage.py: 
python manage.py runserver
python manage.py migrate 
python manage.py shell
3. Explique la diferencia de utilizar urls global y urls local:

4. Escriba un patron de url para una vista basada en funcion 
urlpatterns = [
    url(r'contact/$', views.contact, name='contact'),
]
5. Escriba un patron de url para una vista basada en clase 
urlpatterns = [
path('about/', TemplateView.as_view(template_name="about.html")),
]
6. Escriba el comando para hacer un proyecto en Django:
django-admin.py startproject NombreDeProyecto
7. Escriba el comando para hacer una aplicación en Django:
python manage.py startapp NombreDeAplicación 
8. Mencione para qué sirve el archivo Settings.py:
Para visualizar las configuraciones que se pueden modificar y/o actualizar.
9. Escriba el comando para registrar las migraciones de los modelos:
python manage.py migrate 
10. Escriba el comando para sincronizar el modelo con el motor de base de datos:
