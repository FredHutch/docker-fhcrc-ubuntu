# docker-fhcrc-ubuntu
Freeze official ubuntu docker image for reproducibility.

It appears that the official ubuntu dockerhub images offer a limited number of tags, and just 'ubuntu' is updated willy-nilly.

This repo exists to provide a frozen ubuntu version so a specific version can saved and used.

Note that rebuilding from this Dockerfile will not produce the same image if the upstream 'ubuntu' image has been modified, but we plan to keep all builds in our dockerhub repo (https://hub.docker.com/r/fredhutch/ls2-ubuntu/) with version tags so the images can be re-used.
