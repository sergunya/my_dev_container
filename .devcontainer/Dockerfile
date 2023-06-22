FROM golang:1.20
LABEL authors="sergey.larionov"


RUN useradd -m -d /home/user -s /bin/bash user && adduser user sudo && \
    echo '%sudo ALL=(ALL) NOPASSWD:ALL' >> /etc/sudoers

USER user

WORKDIR /home/user/my_dev_container