FROM alpine:latest
RUN apk update
RUN apk add openntpd

ADD ntpd.conf /etc/ntpd.conf

ENTRYPOINT ["ntpd"]
CMD ["-d" ,"-f", "/etc/ntpd.conf", "-s"]
