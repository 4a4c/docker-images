FROM centos:centos7
MAINTAINER JL

CMD ["bash"]

# update
RUN yum update -y

# basic
RUN yum install -y \
  bash \
  bash-completion \
  curl \
  tar \
  zip

# top tools
RUN yum install -y \
  htop \
  iftop \
  iotop

# net tools
RUN yum install -y \
  net-tools \
  nmap \
  tcpdump

# cleanup
RUN yum clean all
