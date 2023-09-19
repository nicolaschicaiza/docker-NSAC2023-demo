FROM python:3.9

# Instala Django
RUN pip install Django

# Instala TensorFlow
RUN pip install tensorflow

# Establece el directorio de trabajo en /app
WORKDIR /app

# Copia los archivos de tu proyecto al contenedor
COPY . /app

# Comando para ejecutar tu aplicación Django
CMD python manage.py runserver 0.0.0.0:8000
