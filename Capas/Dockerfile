# Capa 1: La imagen base
FROM ubuntu:latest
# Capa 2: Actualizar el sistema
RUN apt-get update && apt-get install -y curl
# Capa 3: Copiar archivos de la aplicación
COPY . /app
# Capa 5: Ejecuta un comando de terminal.
CMD ["echo", "Hello, World!"]