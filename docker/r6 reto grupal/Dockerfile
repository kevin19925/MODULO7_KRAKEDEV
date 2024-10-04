# Especificar la imagen base de Ubuntu
FROM ubuntu:latest

# Etiquetar la imagen con el nombre del mantenedor
LABEL maintainer="kevinqui199925@gmail.com"

# Actualizar el sistema operativo e instalar las herramientas necesarias en una sola capa
RUN apt-get update && apt-get -y upgrade && \
    apt-get install -y curl iputils-ping telnet git vim wget net-tools

# Mantener el contenedor activo ejecutando un comando en ciclo infinito
CMD ["tail", "-f", "/dev/null"]