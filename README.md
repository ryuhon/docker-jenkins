# docker-jenkins
CI/CD with docker swarm cluster.


# How To Build 

```
sudo docker build -t docker-jenkins .
```

# deploy 

```
docker stack deploy -c jenkins.yml jenkins
```
