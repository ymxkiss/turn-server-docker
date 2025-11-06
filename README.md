# Docker image for TURN server
A Docker container with the [Coturn TURN server](https://github.com/coturn/coturn)

sudo docker run -d --name=turn-server -p 3478:3478 -p 3478:3478/udp --restart=always ghcr.io/ymxkiss/turn-server:latest myturn 123456789 realm
