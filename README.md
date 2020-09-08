# This is old version. Please, find the actual version [here](https://github.com/puzl-ee/docker-images/tree/dev/images/h2o4gpu).

H2O is a fully open source, distributed in-memory machine learning platform with linear scalability. Non-root Docker image with CUDA, used by [puzl.ee](https://puzl.ee) Kubernetes cloud provider. 

#### Build:

```
docker build \
    --build-arg H2O_VERSION=3.30.0.1 \
    -t puzlcloud/h2o:3.30.0.1 .
```
