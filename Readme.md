# riscv docker images

copied and adjusted some existing images to be built for riscv, used debian:unstable as base as it has a riscv image available

**UNTESTED, POTENTIALLY UNSTABLE, NO SUPPORT PROVIDED, USE AT OWN RISK**

## node

adjusted from https://github.com/nodejs/docker-node/tree/main/18/buster

using https://unofficial-builds.nodejs.org/ riscv build

published to `thepiwo/node:18-debian-unstable` 

## nginx

adjusted from https://github.com/nginxinc/docker-nginx-unprivileged/tree/main/mainline/debian

[Apache License 2.0](https://raw.githubusercontent.com/nginxinc/docker-nginx-unprivileged/main/LICENSE)

published to `thepiwo/nginx:debian-unstable` 