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

```
docker run -d -t 5000:5000 'image_name'
```

* -d -> detach

To check how many Containers are running currently:

```
docker ps
```

To stop the current running Container:

```
docker stop 'container_id'
```

To remove an existing docker image:

```
docker image rm -f start-app
```

To change the name of a docker image:

```
docker tag start-app kshitiijj/start-app
```

```
docker tag 'old_name' 'new_name'
```

To push the image to the Docker Hub:

```
docker push 'image_name':latest
```
