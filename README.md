# docker-1

docker 101 from 42 Silicon Valley

## setup for 42 lab computers

cd ~ && rm -rf Library/com.docker.docker &&

mkdir /goinfre/mydocker && 

ln -s /goinfre/mydocker Library/com.docker.docker

## running teamspeak

docker build *folder* -t *name*:*tag*

docker run -p 9987:9987/udp -p 10011:10011 -p 30033:30033 -e TS3SERVER_LICENSE=accept *name*:*tag*

ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDGn46c0WirlYJGB4/+IrVB9V2gRzzp3AT4l20hJxVjt6TCkH0lL8pyptxymnjZ2eZH+brG7pjfOzGnEPVAqj5DEYZ/EPsDNEdb4zth1MPLq8wVU/kRejKMI/y0gS2fn1mbp1ti/eBRlbIGA/FgNuRJzfQYO3b5lp/zPBvUJtDA9wrvSqZ/ixJE+xyF3105VHdmLmb0/i1NJ9HcMYYq0aUOuepb47xMx2+sz3ORz/psUVZi2L1d19qe8P7SxpK5TKR+BCF/btTudN444HXFKJ4fkk5bYe7tegf8x2mfbl7BYbvOlncVEW+saCiMtRTtPfJzsdCzp2PjC399Vznma5JF calamber@e1z2r8p17.42.us.org