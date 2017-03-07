FROM anapsix/alpine-java

MAINTAINER Ferreol Soulez ferreol.soulez@epfl.ch

ENV  XMS=10G 

# do all in one step
RUN  	mkdir /usr/src && \
	mkdir /usr/src/icy && \ 
	cd /usr/src/icy && \
	wget https://github.com/FerreolS/Icy-App/archive/master.zip && \
	unzip icy.zip && \
	rm icy.zip 