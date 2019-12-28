ansible script for Ubuntu 18.04

* docker
* microk8s
* helm

To use docker without sudo
```
usermod -aG docker your-user-name
sg docker -c "bash"
docker version
```