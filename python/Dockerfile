FROM ubuntu
RUN echo "deb http://archive.ubuntu.com/ubuntu precise main universe" > /etc/apt/sources.list \
	&& apt-get update \
	&& apt-get upgrade -y \
	&& apt-get install -y language-pack-en
ENV LANGUAGE en_US.UTF-8
ENV LANG en_US.UTF-8
ENV LC_ALL en_US.UTF-8
RUN locale-gen en_US.UTF-8
RUN dpkg-reconfigure locales
RUN apt-get install -y libxml2-dev curl python make gcc wget sqlite3
RUN apt-get install -y postgresql-client-9.1 postgresql-client-common
RUN wget https://bootstrap.pypa.io/ez_setup.py
RUN python ez_setup.py
RUN wget https://bootstrap.pypa.io/get-pip.py
RUN python get-pip.py
