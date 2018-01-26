# CentOS Docker Container for FISPACT-II
[![](https://img.shields.io/docker/pulls/fispact/centos.svg?style=flat)](https://hub.docker.com/r/fispact/centos) [![](https://img.shields.io/docker/build/fispact/centos.svg?style=flat)](https://hub.docker.com/r/fispact/centos) [![](https://images.microbadger.com/badges/license/fispact/centos.svg)](https://microbadger.com/images/fispact/centos)

This repository contains automated builds of CentOS images with the dependencies for [FISPACT-II](http://fispact.ukaea.uk).

For a complete list of Docker images for FISPACT-II, see the [FISPACT-II wiki](https://fispact.ukaea.uk/wiki/Docker_images).

Available on the Docker Hub as [fispact/centos](https://hub.docker.com/r/fispact/centos/).

### Images
The following images are included in this repository, tagged by their operating system version, compiler version and (for some systems) whether or not they include compressed nuclear data libraries for FISPACT-II:
- [![](https://images.microbadger.com/badges/image/fispact/centos:7.4_gfortran_6.svg)](https://microbadger.com/images/fispact/centos:7.4_gfortran_6) `7.4`, `gfortran-6`, [Dockerfile: *fispact/centos:7.4_gfortran_6*](https://github.com/fispact/docker_centos/blob/7.4_gfortran_6/Dockerfile)
- [![](https://images.microbadger.com/badges/image/fispact/centos:6.9_gfortran_6.svg)](https://microbadger.com/images/fispact/centos:6.9_gfortran_6) `6.9`, `gfortran-6`, [Dockerfile: *fispact/centos:6.9_gfortran_6*](https://github.com/fispact/docker_centos/blob/6.9_gfortran_6/Dockerfile)
- [![](https://images.microbadger.com/badges/image/fispact/centos:6.9_gfortran_6_data.svg)](https://microbadger.com/images/fispact/centos:6.9_gfortran_6_data) `6.9`, `gfortran-6`, `data`
