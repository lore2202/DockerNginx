# DockerNginx
Práctica de Dockers utilizando el servidor Nginx.

Para construir la imagen: docker build -t imagen_nginx:1.0 .

Para ejecutarla: docker run -d -p 80:80 --name contenedor_nginx imagen_nginx:1.0
