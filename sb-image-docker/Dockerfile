FROM alpine:3.8

RUN mkdir /ansible

WORKDIR /ansible

COPY . .

RUN chmod +x script.sh

CMD ["/bin/sh"]
