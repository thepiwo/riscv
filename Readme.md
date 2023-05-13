# riscv docker images

copied and adjusted some existing images to be built for riscv, used debian:unstable as base as it has a riscv image available

**UNTESTED, POTENTIALLY UNSTABLE, NO SUPPORT PROVIDED, USE AT OWN RISK**

## node

adjusted from https://github.com/nodejs/docker-node/tree/main/18/buster

using https://unofficial-builds.nodejs.org/ riscv build

published to `thepiwo/node:18-debian-unstable` 

## nginx

somewhat trivial implementation, not sure if that's sufficient

published to `thepiwo/nginx:debian-unstable` 