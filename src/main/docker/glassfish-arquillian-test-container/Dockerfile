FROM reap/docker-glassfish3
MAINTAINER Ilari Liukko "ext_ilari.liukko@samlink.fi"

# create domain
RUN /create_domain.sh hairionetti 13000

# expose domains admin and http-port
EXPOSE 13048 13080
