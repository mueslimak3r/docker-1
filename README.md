# docker-1

docker 101 from 42 Silicon Valley

## setup for 42 lab computers

cd ~ && rm -rf Library/com.docker.docker

mkdir /goinfre/docker

ln -s /goinfre/docker Library/com.docker.docker

## running teamspeak

docker build *folder* -t *name*:*tag*

docker run -p 9987:9987/udp -p 10011:10011 -p 30033:30033 -e TS3SERVER_LICENSE=accept *name*:*tag*