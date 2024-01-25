FROM python:3.10
LABEL MAINTAINER="Nathan Pretorius nathanpretorius@icloud.com"

ENV TERM xterm
ENV DEBIAN_FRONTEND noninteractive

RUN \
    apt-get -y update && \
    apt-get -y upgrade 

RUN \
    apt-get -y install curl wget 

RUN apt-get -y install build-essential cmake git unzip pkg-config 

RUN git clone https://github.com/npretor/pcb-tools.git && \
    cd pcb-tools && \
    python -m pip install -r requirements.txt && \
    python setup.py install 