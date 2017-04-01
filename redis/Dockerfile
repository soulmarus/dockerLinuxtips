FROM komljen/ubuntu
MAINTAINER Daniel Souza <daniel.mf.souza@gmail.com>

RUN \
  add-apt-repository -y ppa:chris-lea/redis-server && \
  apt-get update && \
  apt-get -y install \
		redis-server && \
  rm -rf /var/lib/apt/lists/*



CMD ["/usr/bin/redis-server"]

EXPOSE 6379
