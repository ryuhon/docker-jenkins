# docker-jenkins
docker swarm 환경에서 CI/CD를 사용하기 위해 jenkins 이미지를 찾다가 마땅히 없어서 
http://pragmaticstory.com/?p=113 글을 참조해서 빌드.

docker-compose파일은 docker swarm 과 treafik 환경에서 사용할수 있음. 

# How To Build 

```
sudo docker build -t docker-jenkins .
```

# deploy 

```
docker stack deploy -c jenkins.yml jenkins
```
