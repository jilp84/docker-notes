# Notas de Docker

### Comandos basicos

```bash
# Saber la versión instalada de docker
docker --version

# Obtener la información de docker
docker info

# Hola mundo con docker
$ docker run hello-world

# Ver contenedores corriendo
$ docker ps

# Ver todos los contenedores
$ docker ps -a

# Inspecionar la config un contenedor
$ docker inspect <container_id or container_name>

# Crear un contenedor con un nombre personalizado
$ docker run --name <custom_name> <image_name>

# Renombrar un contenedor
$ docker rename --name <old_name> <new_name>

# Eliminar un contenedor
$ docker rm <container_id or container_name>

# Eliminar todos los contenedores apagados
$ docker container prune

# Eliminar TODOS los contenedores
$ docker rm -f $(docker ps -aq)

# iniciar contenedor de ubuntu
docker run -it ubuntu

# Detener contenedor
docker stop <container_id or container_name>
```

https://collectednotes.com/barckcode/docker-cheat-sheet
