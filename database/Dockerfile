# Usa la imagen base de MySQL 5.7
FROM mysql:5.7

# Variables de entorno para configuración de MySQL
ENV MYSQL_DATABASE=mydatabase \
    MYSQL_USER=myuser \
    MYSQL_PASSWORD=mypassword \
    MYSQL_ROOT_PASSWORD=rootpassword

# Copia los archivos de inicialización de la base de datos al contenedor
COPY ./database-scripts/ /docker-entrypoint-initdb.d/

# Puerto por defecto de MySQL
EXPOSE 3306


