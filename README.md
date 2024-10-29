# learning-docker

```
docker pull kshitiijj/node_docker:latest
```

## Docker cmd's

**BULD Image**
    ```
    docker build -t kshitiijj/node_docker:1.0 .
    ```

**RUN Image to make Container**
    ```
    docker run -p 5000:8080 kshitiijj/node_docker:1.0
    ```

**VOLUMES**
    ```
    docker volume create shared-stuff
    ```

*MOUNT Volume*
    ```
    docker run -p 5000:8080 --mount source=shared-stuff,target=/stuff kshitiijj/node_docker:1.0
    ```

**Docker Compose**
    ```
    docker-compose up
    ```