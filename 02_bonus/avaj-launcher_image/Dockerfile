FROM debian

RUN apt-get update  && apt-get install -y default-jdk && apt-get install -y maven

RUN git clone https://github.com/tshata/avaj_launcher.git

WORKDIR tshata

RUN mvn clean package
