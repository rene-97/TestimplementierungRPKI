FROM nicmx/fort-validator

#COPY tals/ /etc/fort/tal/
RUN mkdir  /etc/fort/slurm/ /etc/fort/tal
RUN fort --init-tals --tal /etc/fort/tal
#COPY fort.conf /etc/fort/fort.conf
#RUN fort -t /etc/fort/tal/ --server.address 173.16.238.13 --server.port 3323 --server.interval.validation 1800