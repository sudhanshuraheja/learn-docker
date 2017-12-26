$ docker images
$ docker images -a
$ docker pull alpine:latest

$ docker run alpine uname -v
$ docker run --interactive --tty alpine sh
$ docker run -it alpine sh
$ docker run -d alpine ping google.com
$ docker run -d --name test_name alpine ping google.com

$ docker ps
$ docker inspect alpine
$ docker kill alpine
$ docker rmi alpine
