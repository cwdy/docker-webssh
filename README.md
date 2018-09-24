# docker-webssh
Run webssh in docker

## [docker](http://www.docker.com)
Don't know? I am pretty sure this project is not what you are looking for. Just skip it. 
Honestly, I am also studying it, can not say much but really a cool tool you will like. Don't hesitate to try it!

## [webssh](https://github.com/huashengdun/webssh)
A simple web SSH client. Written in Python.

## How to use
To start a container from this image:
``` bash
$ docker run -d -p 8080:8080 snsyzb/webssh
```
The container will start a web application on 8080 port, so you can visit your own ssh client web application via openning localhost:8080 in your browser.
Or you could use command parameter in docker run to identify the address and port:
``` bash
$ docker run -d -p 10000:10000 snsyzb/webssh wssh --address=0.0.0.0 --port=10000
```
The command above will start running a container listening the port 10000
