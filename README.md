# docker-alert
docker container health check alerts

## Just run this
```cmd
    git clone https://github.com/sidjhappyhigh/docker-alert.git
    cd docker-alert 
    docker run -d --name healtcheck \
    -v /var/run/docker.sock:/var/run/docker.sock \
    -v conf.yml:/app/conf.yml \
    quaide/dem:latest
    docker logs healtcheck
```
