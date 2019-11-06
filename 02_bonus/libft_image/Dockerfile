FROM debian

RUN apt-get update && apt-get install -y build essential vim git

RUN git clone https://github.com/tshata/libft

WORKDIR libft

RUN make
