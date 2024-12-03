Antora generation image
=======================

This image is a modification of the upstream Alpine-based
image to contain a few additional extensions


## Usage instructions
```shell
$ podman run -v $PWD:/workspace \
    quay.io/crc-org/antora:3.1.9 \
    antora-playbook.yml
```
