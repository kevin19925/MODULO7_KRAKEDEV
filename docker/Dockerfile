
# Especificar la imagen base de Ubuntu
FROM ubuntu:latest

# Etiquetar la imagen con el nombre del mantenedor
LABEL maintainer="kevinqui199925@gmail.com"

# Actualizar el sistema operativo y instalar las herramientas necesarias
RUN apt-get update
RUN  apt-get -y upgrade
RUN   apt-get install -y curl 
RUN apt-get install -y iputils-ping 
RUN  apt-get install -y telnet

# Mantener el contenedor activo ejecutando un comando en ciclo infinito
CMD ["tail", "-f", "/dev/null"]
