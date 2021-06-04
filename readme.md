# Bienvenido a la librería de encuestas de Python

A continuación vamos a explicar cómo instalar el proyecto

1. Descarga el código con el siguiente comando.

>git clone https://github.com/joseluisGA/django_polls.git

2. Creamos el entorno virtual con el comando:

>python3 -m venv .venv

3. Activamos el entorno virtual

>source .venv/bin/activate

4. Instalamos las librerías necesarias que se encuentran en el fichero "requeriments.txt".

>pip install -r requirements.txt 

5. Ejecutamos la migraciones.

>python manage.py migrate

6. Cargamos los datos iniciales

>python manage.py loaddata fixtures/polls_data.json

7. Configurar localhost como ip permitida para django. Editar el fichero 'django_polls/settings.py'.

8. Arrancamos el servidor.