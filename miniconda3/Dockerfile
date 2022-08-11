FROM ubuntu
LABEL maintainer=@joshuacook
ARG UBUNTU_FRONTEND=noninteractive
RUN apt update --fix-missing && \
    apt install -y \
    wget bzip2 ca-certificates \
    libglib2.0-0 libxext6 libsm6 libxrender1 