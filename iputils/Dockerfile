FROM sfoubert/my_ubuntu:latest

RUN \
  apt-get update && \
  apt-get -y install iputils-ping

ENTRYPOINT ["ping"]
CMD ["127.0.0.1"]


