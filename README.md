# Electiva2-Practica-Ejecutar-Servidor-Web-Nginx-Con-Docker


# Práctica: Servidor web Nginx con Docker Compose

## Descripción

Esta práctica consiste en crear y ejecutar un servidor web local utilizando **Nginx y Docker Compose**. Se creó una página web básica en HTML con el mensaje "Hola mundo" y se configuró un archivo `docker-compose.yml` para ejecutar el servidor dentro de un contenedor Docker.

Se utilizó un volumen para compartir el directorio `src` con la ruta `/usr/share/nginx/html` del contenedor, permitiendo que Nginx sirva la página web sin necesidad de reconstruir la imagen.

## Tecnologías utilizadas

- Docker
- Docker Compose
- Nginx
- HTML

## Ejecución

Para iniciar el servidor web, ejecutar el siguiente comando desde el directorio del proyecto:

```bash
docker compose up -d
```

Luego, acceder desde el navegador a:

http://localhost:8080

## Autor

Joel Alberto Benitez Varela -  `https://github.com/JoelAlBenitez` 
