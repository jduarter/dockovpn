# docker-openvpn
Out of the box openvpn server docker image which you can use anywhere

## To run Ubuntu in docker
`docker run -it --rm --name ubuntu-openvpn --mount type=bind,source="$(pwd)"/scripts,target=/opt/teleport  ubuntu:16.04`