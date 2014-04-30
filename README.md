# docker-debian-rvm

a Dockerfile for stable rvm on stable Debian

## how to

### install

install [Docker](https://www.docker.io/gettingstarted/#h_installation)

```
git clone https://github.com/ahdinosaur/docker-debian-rvm
```

### build

```
docker build -t ahdinosaur/debian-rvm .
```

### run

```
docker run -i -t ahdinosaur/debian-rvm /bin/bash --login
```

### publish

```
docker push ahdinosaur/debian-rvm
```
