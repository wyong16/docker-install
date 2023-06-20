# docker-install
![](https://img.shields.io/github/stars/Jrohy/docker-install.svg)
![](https://img.shields.io/github/forks/Jrohy/docker-install.svg) 
![](https://img.shields.io/github/license/Jrohy/docker-install.svg)  
auto install latest docker by online/offline (binaries install)

## Install/Update docker online
```
source <(curl -sL https://docker-install.netlify.app/install.sh)
```

## Install docker by official shell(get.docker.com)
```
source <(curl -sL https://docker-install.netlify.app/install.sh) -s
```

## Install/Update docker offline
```
./install.sh -f /root/docker-20.10.6.tgz
```
bash-completion file **docker.bash** should put same directory with install.sh  
offline file: https://download.docker.com/linux/static/stable/
