# En este ejemplo aprenderemos como crear variables de entorno y 
# a usar la instruccion WORKDIR
#

FROM ubuntu

ENV AUTHOR_NAME "Federico Martinez E."
ENV PATH_DIR "/home/fdxsoft/"

# Con este comando indicamos el directorio base de nuestra aplicacion
# Y al correr el contenedor en modo interactivo nos metera directamente
# dentro de esa carpeta
WORKDIR /home
# Con el punto indicamos que el archivo se copiara dentro del directorio base
COPY secreto.txt .
# Tambien podemos hacer COPY usando paths en variables de entorno
COPY secreto.txt ${PATH_DIR}








