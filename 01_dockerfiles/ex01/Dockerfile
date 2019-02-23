FROM debian
RUN apt-get update -y && apt-get upgrade -y && \
    apt-get install -y bzip2 wget && \
    wget https://files.teamspeak-services.com/releases/server/3.6.1/teamspeak3-server_linux_amd64-3.6.1.tar.bz2 && \
    bunzip2 *.bz2 && \
    tar -xvf *.tar
CMD ["sh", "teamspeak3-server_linux_amd64/ts3server_minimal_runscript.sh"]