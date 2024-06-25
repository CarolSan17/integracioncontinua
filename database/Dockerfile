# Usar la imagen oficial de MySQL
FROM mysql:latest

# Configurar variables de entorno necesarias
ENV MYSQL_DATABASE=mydatabase
ENV MYSQL_USER=myuser
ENV MYSQL_PASSWORD=mypassword
ENV MYSQL_ROOT_PASSWORD=rootpassword

# Exponer el puerto 3306
EXPOSE 3306

# Copiar archivos de inicialización si es necesario
# COPY init.sql /docker-entrypoint-initdb.d/
