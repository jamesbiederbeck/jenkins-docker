# jenkins-docker

This is the repo I use to run jenkins on my raspberry pi 4!

This will let you run Jenkins in Docker, while also building inside of docker containers. 
It's 2022, quit running jenkins on bare metal!

To get started:

```bash
docker build -t myjenkins-blueocean:1.2 .
docker-compose up -d
```
