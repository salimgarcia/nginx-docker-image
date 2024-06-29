My first custom Docker image made by following [this](https://www.youtube.com/watch?v=SnSH8Ht3MIc&list=LL&index=3) tutorial

Runs an nginx server and serves a simple webpage

`docker pull ghcr.io/salimgarcia/nginx-webserver:latest`

`docker run -d -p 80:80 [IMAGE ID]`