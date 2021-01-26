# FROM scrapy
FROM gcr.io/perfect-period-295613/scrapy:latest

RUN apt-get install opam -y
RUN opam init --disable-sandboxing
RUN opam update
RUN apt-get install pkg-config -y
RUN opam switch install 4.11.1+flambda
RUN apt-get install libev-dev -y
RUN opam install -y opium
RUN opam install -y atdgen
RUN opam install -y dune
