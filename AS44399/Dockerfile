FROM frrouting/frr:latest

RUN apk update

COPY frr.conf /etc/frr/frr.conf
COPY daemons /etc/frr/daemons
COPY vtysh.conf /etc/frr/vtysh.conf