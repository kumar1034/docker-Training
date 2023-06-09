
Dockerfile is a declarative way of creating our own images. Docker will give us some syntax to create our own images.

File name should Dockerfile. docker command should run where your Dockerfile exists.

**How to build image from Dockerfile**

Docker Architecture
Docker architecture consists of

Docker client which is shell
Docker daemon
Docker Registry
Docker objects
Images
Containers
Docker networking
Docker storage

```
docker build -t [docker-hub-URL]/[your-username]/[image-name]:version .
```

**How to run container from image**
```
docker run -itd [image-name]:version .
```

**How to push image to Dockerhub**

```
docker push [docker-hub-URL]/[your-username]/[image-name]:version
```

**Docker Architecture**

![docker-architecture](https://user-images.githubusercontent.com/8718083/231742683-b1360068-a38a-466d-be5c-ebd75e601e8f.png)

