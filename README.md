# Java 8 (1.8.0_111)
### based on Ubuntu 16.04 (Xenial Xerus)
----
### Pull from Docker Hub
```
docker pull beevelop/java:latest
```

### Build from GitHub
```
docker build -t beevelop/java github.com/beevelop/docker-java
```

### Run image
```
docker run -it beevelop/java bash
```

### Use as base image
```Dockerfile
FROM beevelop/java:latest
