# multi-stage-dockerfile
```
1  [ ! -d 'guestbook' ] && git clone https://github.com/ibm-developer-skills-network/guestbook
2  cd guestbook
3  ls
4  cd v1/guestbook
5  docker build . -t pluto:v1
6  docker images
7  docker run -dp 3000:3000 pluto:v1
8  docker ps -a
9  curl localhost:3000
10  history
```
