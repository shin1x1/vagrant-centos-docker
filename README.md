# Usage

## vagrant up

```
$ git clone https://github.com/shin1x1/vagrant-centos-docker.git
$ cd vagrant-centos-docker
$ vagrant up
```

## build docker image

```
$ docker build -t sample .
```

## run docker container

```
$ docker run -p 80:80 -v /vagrant:/vagrant -d sample
```

## access to httpd container

http://192.168.33.10/

