# Usa la imagen base de nginx con Alpine
FROM nginx:alpine

# Elimina el contenido por defecto del directorio HTML de nginx
RUN rm -rf /usr/share/nginx/html/*

# Copia los archivos del sitio web al directorio de trabajo en el contenedor
COPY ./ /usr/share/nginx/html

# Puerto por defecto de nginx
EXPOSE 80

