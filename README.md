# wireguard-docker for the arm32 boards
Wireguard setup in Docker for Raspberry Pi, odroid xu4, generally all arm32 based boards. 

Based on https://github.com/cmulk/wireguard-docker. Have a look there for documentation. 



## Host system preparation

    sudo apt-get install linux-headers-generic

    sudo apt-get install linux-generic




    docker build  -t wireguard:local github.com/brandrik/wireguard_docker_arm







