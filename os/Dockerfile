FROM ubuntu
WORKDIR /workdir
COPY . ./
RUN bash ./scripts/start-log-script.sh
#RUN apt update
#RUN apt upgrade
#RUN apt install neofetch -y >> neo.log

#RUN bash ./scripts/install-script.sh

RUN apt update
RUN apt install neofetch -y >> neo.log
RUN command
CMD ["bash"]