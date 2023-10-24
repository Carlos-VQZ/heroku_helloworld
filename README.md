# Configuracion basica de heroku y FastApi

Heroku hello world FastAPI

## Lista de archivos
Archivos de configuracion necesarios para ejecutar la API

|No.|Archivo|descipcion|
|--|--|--|
|1| .gitignore|Archivos y de¿irectorios que no se suben al repositiorio|
|2| requirements.txt|Librerias necesarias para ejecutar la api|
|3| runtime.txt|Version de pyhton que se usara en heroku|
|4| Procfile|
|5| main.py|
|6| README.md|

## Run API
gunicorn -k uvicorn.workers.UvicornWorker --bind 0.0.0.0:$PORT main:app
