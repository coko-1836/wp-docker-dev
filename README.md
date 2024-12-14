# wp-docker-dev
wordpressの開発環境を構築するのがめんどくさいのでdocker環境で使えるようにする汎用repo

## 使い方
0. install docker desktop  
https://www.docker.com/products/docker-desktop
1. clone this repo
```bash
git clone https://github.com/coko-1836/wp-docker-dev.git
```
2. run docker-compose
```bash
cd {this repo}
docker-compose up -d
```
3. open <a href="http://localhost:8080">http://localhost:8080</a>