FROM ubuntu:18.04

ENV DEBIAN_FRONTEND noninteractive

RUN apt-get update
RUN apt-get install -yq build-essential \
    python-dev \
    python3-minimal \
    python3-pip \
    python3-dev \
    python3-venv 

ENTRYPOINT bash

# Build: docker build --tag=demo .
# Run (Bandera para borrar en cuanto la máquina se apaga): docker run --rm -it demo
# Exit (Salir del Contenedor): exit