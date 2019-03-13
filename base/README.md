# Base Docker images for Redash production and development images.

## `debian`

A Docker image based on the official Python Docker image (Debian based).

`redash/base:debian`

## `ubuntu`

A Docker image based on the Ubuntu Xenial Docker image.

This is the current base Docker image for the `redash/redash` image.

`redash/base:latest`

## `oracle`

Image based on `redash/base:xenial` which installs Oracle's Instant Client. To use
this image, you need to accept the license [on this page](https://www.oracle.com/technetwork/topics/linuxx86-64soft-092277.html).

`redash/base:oracle`
