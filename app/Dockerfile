# Usamos imagen base de Python
FROM python:3.9-slim

# Establecer directorio de trabajo
WORKDIR /app

# Copiar archivos
COPY requirements.txt requirements.txt
RUN pip install -r requirements.txt

COPY . .

# Comando para ejecutar la app
CMD ["python", "app.py"]
