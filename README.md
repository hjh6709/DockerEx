# DocekrEx 깃헙과 연동 예제

## Installation
```bash
cd ~
cd DEV
cd gitEx
git clone https://github.com/hjh6709/DockerEx.git
cd DockerEx

## Run
```bash
#Login for Private Docker Repository
docker login
docker pull hjh427/docerex
docker run docker run -p 80:80 \ -v /home/umhaha/gitEx/DockerEx/Project:/var/www/html \ hjh427/dockerex
