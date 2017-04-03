FROM ubuntu:16.04
MAINTAINER Sebastien Foubert "sebastien.foubert@gmail.com"

ENV INTELLIJ_VERSION 2017.1-no-jdk

RUN apt-get update
RUN apt-get install -y curl

RUN curl http://download-cf.jetbrains.com/idea/ideaIU-${INTELLIJ_VERSION}.tar.gz > /opt/ideaIU-${INTELLIJ_VERSION}.tar.gz && \
    cd /opt && \
    tar xvzf ideaIU-${INTELLIJ_VERSION}.tar.gz && \
    rm -f ideaIU-${INTELLIJ_VERSION}.tar.gz && \
    mv /opt/idea* /opt/idea

CMD ["/opt/idea/bin/idea.sh"]
