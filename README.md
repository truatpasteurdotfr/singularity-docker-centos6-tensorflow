# singularity-docker-centos6-tensorflow
singularity recipe for bootstrapping a tensorflow build container from a centos:centos6 docker image

```
sudo singularity create -s 3600 singularity-docker-centos6-tensorflow.img
sudo singularity bootstrap singularity-docker-centos6-tensorflow.img Singularity
```
