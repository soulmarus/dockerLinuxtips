FROM httpd:2.4
MAINTAINER Daniel Macario <daniel.mf.souza@gmail.com>

LABEL "com.example.vendor"="Damtech Incorporated"
LABEL com.example.label-with-value="Linuxtips"
LABEL version="1.0"
LABEL description="Imagem da segunda aula do fodastico curso de docker na LinuxTips"

COPY ./html /usr/local/apache2/htdocs
ADD app.tar /usr/

#RUN echo "<html><body><h1>Daniel Rulez!</h1></body></html>" > /usr/local/apache2/htdocs/index.html

