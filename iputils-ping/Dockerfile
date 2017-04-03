FROM ubuntu:16.04

RUN apt-get update && apt-get install -y iputils-ping

ENTRYPOINT ["ping"]

CMD ["127.0.0.1"]
