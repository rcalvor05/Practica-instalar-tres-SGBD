# Instalación SGBD

## Características de la VM
![Características](imagenes/captura01.png)

## Preparamos Podman y descargamos la imagen
##### `sudo apt update`
Actualizamos todos los paquetes (esto no descarga las actualizaciones solo los actualiza)
##### `sudo apt install podman`
Descargamos Podman
##### `sudo podman pull container-registry.oracle.com/database/free:23.5.0.0`
Descargamos la iamgen de contenedor pero no la ejecutamos
##### `sudo podman images`
Lista las imagenes que tenemos instaladas en el equipo
