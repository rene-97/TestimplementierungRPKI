FROM frrouting/frr:v7.3.0
RUN apk update

COPY frr.conf /etc/frr/frr.conf
COPY daemons /etc/frr/daemons
COPY vtysh.conf /etc/frr/vtysh.conf