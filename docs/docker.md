# Contenedor Docker con NGINX 

## Creación del contenedor 


```bash
# Crear el contenedor NGINX
docker run -d \
  --name PPS-Unidad0-Tarea-Serrano_Sanchez_Adrian \
  -p 8085:80 \
  -v $(pwd):/usr/share/nginx/html \
  nginx:alpine
```

vamos a `http://localhost:8085/`

![Imagen Docker](imagenes/dockers.png)
