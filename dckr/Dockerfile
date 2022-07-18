FROM ubuntu:20.04
ENV DEBIAN_FRONTEND noninteractive

ADD ./space2.sh /home/alev/dckr/space2.sh

#RUN apt-get update && apt-get install -y --no-install-recommends apt-utils

RUN apt-get update && apt-get install -y apt-utils

RUN apt-get install -y bc 
RUN apt-get install -y lsb-release

RUN chmod +x /home/alev/dckr/space2.sh

CMD ["/home/alev/dckr/space2.sh"]


ENV DEBIAN_FRONTEND teletype
