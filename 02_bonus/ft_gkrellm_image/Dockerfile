FROM debian

RUN apt-get update -y  && apt-get install -y build-essential git vim

RUN git clone https://github.com/tshata/ft_gkrellm.git

WORKDIR ft_gkrellm

RUN make

ENTRYPOINT ./ft_gkrellm
