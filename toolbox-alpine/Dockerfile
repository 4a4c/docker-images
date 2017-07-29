FROM alpine
MAINTAINER JL

CMD ["bash"]

# update
RUN  apk update

# basic necessities
RUN apk add --no-cache \
  bash \
  bash-completion \
  tzdata \
  curl \
  tar \
  zip

# top/perf tools
RUN apk add --no-cache \
  htop \
  iotop \
  iftop


# net tools
RUN apk add --no-cache \
  net-tools \
  nmap \
  tcpdump
