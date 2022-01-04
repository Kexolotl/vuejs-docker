# vuejs-docker

## Project setup

### Compiles and hot-reloads for development
```
docker-compose up
```

### Compiles and minifies for production
```
docker build -t vuejs-docker .
docker run -it -d -p 8000:80 --rm vuejs-docker
```

### Stop container
```
docker container kill <:id>
```