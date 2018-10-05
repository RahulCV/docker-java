# Java 8 (1.8.0_111)
### based on Ubuntu 18.04 (Bionic Beaver)
----
### Pull from Docker Hub
```
docker pull rahulcv/java:latest
```

### Build from GitHub
```
docker build -t rahulcv/java github.com/beevelop/docker-java
```

### Run image
```
docker run -it rahulcv/java bash
```

### Use as base image
```Dockerfile
FROM rahulcv/java:latest
