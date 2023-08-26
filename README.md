# Payara Dockerfile

The Payara team has released [official Docker images](https://hub.docker.com/u/payara/). However, this is only for AMD64 and will not work properly on machines with ARM64 (like the Apple M1) due to inotify issues ([Source](https://github.com/docker/for-mac/issues/6174)).

This Dockerfile provides a Docker image of Payara that works correctly on ARM64.
