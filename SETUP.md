### Setup UNIX v7 on PDP 11

    docker run --rm -it alpine
    vi etc/apk/repositories
    http://dl-cdn.alpinelinux.org/alpine/edge/testing
    apk add simh
    mv /usr/bin/simh-pdp11 /home
    rm /usr/bin/simh-*
    mv /home/simh-pdp11 /usr/bin/
    cd /home
    wget http://simh.trailing-edge.com/kits/uv7swre.zip
    unzip uv7swre.zip
    rm uv7swre.zip
    
### SimH setup file

    vi ini
    set cpu 11/45
    set tto 7b
    att rl unix_v7_rl.dsk
    boot rl
    
**[Reference](http://www.jdpressman.com/2015/11/27/how-to-emulate-unix-v7-using-SIMH-(2015).html)**
