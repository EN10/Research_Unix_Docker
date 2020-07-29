# Research_Unix_Docker
Research UNIX v7 (1979) on PDP 11 using Docker  
COMPRESSED SIZE: 8.44 MB    
IMAGE SIZE: 19.4MB  

[Research Unix](https://en.wikipedia.org/wiki/Research_Unix#Versions)   
[Install Docker](https://docs.docker.com/get-docker) OR [Play with Docker](https://labs.play-with-docker.com)

    docker run --rm -it eniof/unix7 
    
    cd /home  
    simh-pdp11 ini  
    boot  
    rl(0,0)rl2unix  
    
[Docker Setup](https://github.com/EN10/Research_Unix_Docker/blob/master/SETUP.md)   
[Custom Docker Image](https://github.com/EN10/Research_Unix_Docker/blob/master/IMAGE.md)
