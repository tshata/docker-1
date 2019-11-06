FROM debian

RUN apt-get update && apt-get upgrade && apt-get install -y build-essential git vim ruby

RUN git clone https://github.com/tshata/filler.git

WORKDIR /filler
