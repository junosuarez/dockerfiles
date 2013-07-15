# DOCKER-VERSION 0.4.8
FROM base:ubuntu-12.10

RUN apt-get -y install mono-devel autoconf pkg-config make git libtool
RUN git clone https://github.com/fsharp/fsharp
RUN cd fsharp && ./autogen.sh --prefix /usr && make && make install