FROM ubuntu:20.04

RUN apt update && \
    apt install software-properties-common -y && \
    add-apt-repository ppa:vbernat/haproxy-2.1 && \
    apt update -yqq && \
    apt install haproxy=2.0.\* -y

EXPOSE 80

#COPY haproxy.cfg  /etc/haproxy/haproxy.cfg
