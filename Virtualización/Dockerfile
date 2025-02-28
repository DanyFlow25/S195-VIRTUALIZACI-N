#SO y Python
FROM python:3.12-slim
#Crear una carpeta de trabajo
WORKDIR /app
#Importar proyecto de la carpeta
COPY .. /app
#Instalar dependencias
RUN pip install --no-cache-dir -r requirements.txt
#Exponer el puerto
EXPOSE 5000
#Ejecutar el proyecto
CMD ["python", "app.py"]