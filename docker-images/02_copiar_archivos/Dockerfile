FROM ubuntu 

RUN apt update

#OJO: Si vamos a copiar en una carpeta tenermos que terminarla con /
COPY * /home/fdxsoft/

#******* NOTAS: *******
#   - Esto solo funciona para archivos en el mismo path que el Dockerfile, no para carpetas
#   - Podemos especificar un unico archivo por su nombre
#   - Podemos usar el caracter comodin para incluir todos los archivos (incluso el Dockerfile)
#   - Podemos usar el comodin *.extension para indicar que archivos con cierta extension
#     necesitamos copiar en el directorio
#   - El directorio se creara de manera automatica dentro del SO de la imagen.
