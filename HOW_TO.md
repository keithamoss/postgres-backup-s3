```
DOCKER_BUILDKIT=1 docker build --build-arg ALPINE_VERSION=3.16 . -t postgres-backup-s3
docker tag postgres-backup-s3 keithmoss/postgres-backup-s3:15
docker push keithmoss/postgres-backup-s3:15
```
