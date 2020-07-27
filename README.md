# Research_Unix_Docker
Research UNIX v7 (1979) on PDP 11 using Docker

[Research Unix](https://en.wikipedia.org/wiki/Research_Unix#Versions)

[Install Docker](https://docs.docker.com/get-docker)

    docker run --rm -it eniof/unix7 
    
    cd /home  
    simh-pdp11 ini  
    boot  
    rl(0,0)rl2unix  
