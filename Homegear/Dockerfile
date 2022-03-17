# Taken from https://github.com/Homegear/Homegear-Docker/blob/master/rpi-stable/Dockerfile
FROM homegear/homegear:testing
MAINTAINER Clemens Putschli <clemens@putschli.de>

COPY run.sh /run.sh
RUN chmod +x /run.sh
ENTRYPOINT ["/bin/bash", "-c", "/run.sh"]

EXPOSE 2001 2002 2003
