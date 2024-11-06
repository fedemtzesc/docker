FROM ubuntu 

RUN apt update 
LABEL creacion_linux="*** CREANDO EL USUARIO EN LINUX"
RUN useradd federico
LABEL creacion_docker="*** CREANDO USER EN DOCKER ***"
USER federico

CMD echo "bienvenido a tu aplicacion!"
