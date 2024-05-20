# Utilizar una imagen base de Python
FROM python:3.9

# Establecer el directorio de trabajo en /app
WORKDIR /app

# Copiar los archivos necesarios al contenedor
COPY . .

# Instalar las dependencias del proyecto
RUN pip install -r requirements.txt

# Exponer el puerto 8501 para la aplicación Streamlit
EXPOSE 8501

# Comando para ejecutar la aplicación Streamlit
CMD ["streamlit", "run", "app.py"]
