FROM ubuntu:16.04

#MAINTAINER Zach Deibert<zachdeibert@gmail.com>
#MAINTAINER Daniel Guerra <daniel.guerra69@gmail.com>
MAINTAINER Mathias Stadler<stadler-mathias@web.de>



ENTRYPOINT ["/launch.sh"]
CMD [":0"]

RUN  apt-get update && \
        apt-get install -y firefox libcanberra-gtk3-module && \
        apt-get clean 
       
ADD launch.sh /launch.sh
