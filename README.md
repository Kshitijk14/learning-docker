# learning-docker

## Docker cmd's

To buid the Docker Image::

```
docker build -t start-app .
```

To check if the Image is built or not:

```
docker images
```

Run the Docker Image as a Container:

```
docker run -p 5000:5000 start-app
```

To check how many Containers are running currently:

```
docker ps
```

TO stop the current running Container:

```
docker stop 'container_id'
```
