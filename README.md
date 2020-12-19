# Docker  Class Resources
Develop the initial unoptimized Dockerfiles into their optimized counterparts.

## Build initial Java Dockerfile
```bash
time docker build --no-cache -t docker-class-java . -f Dockerfile.initial-java
```

## Build final Java Dockerfile
```bash
time DOCKER_BUILDKIT=1 docker build --no-cache -t docker-class-java --target release --build-arg flavor=jessie ./
```

## Build initial NodeJS Dockerfile
```bash
time docker build --no-cache -t docker-class-node . -f Dockerfile.initial-node
```

## Try improving Dockerfile.initial-nodejs into a Dockerfile.final-nodejs

## Useful links
- [NodeJS Best Practices Gist](https://github.com/nodejs/docker-node/blob/master/docs/BestPractices.md)
- [Bret Fischer on Docker and Node.js best practices](https://youtu.be/Zgx0o8QjJk4)
- [Simplify All the Things with Docker Compose](https://youtu.be/QeQ2MH5f_BE)
