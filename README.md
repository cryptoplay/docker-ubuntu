Ubuntu Docker Image
=======

This git repo provides `docker-apt-install PACKAGE` helper for installing packages.
running [ubuntu](http://releases.ubuntu.com/16.04/) in a Docker container.

Docker needs extra steps to clean up images after installing packages (https://docs.docker.com/engine/userguide/eng-image/dockerfile_best-practices/) and often that apt mirrors failing so we decided to write a helper with Docker's best practices and retries. Use `docker-apt-install PACKAGE` instead of `apt-get install PACKAGE` and installs will be reliable and keep the image as small as possible.

Project:            https://github.com/cryptoplay/docker-ubuntu<br/>
Docker image:       https://registry.hub.docker.com/u/cryptoplay/ubuntu/<br/>

[![Download size](https://images.microbadger.com/badges/image/cryptoplay/ubuntu.svg)](http://microbadger.com/images/cryptoplay/ubuntu "View on microbadger.com")
[![Version](https://images.microbadger.com/badges/version/cryptoplay/ubuntu.svg)](http://microbadger.com/images/cryptoplay/ubuntu "View on microbadger.com")
[![Source code](https://images.microbadger.com/badges/commit/cryptoplay/ubuntu.svg)](http://microbadger.com/images/cryptoplay/ubuntu "View on microbadger.com")
[![Docker Registry](https://img.shields.io/docker/pulls/cryptoplay/ubuntu.svg)](https://registry.hub.docker.com/u/cryptoplay/ubuntu)&nbsp;
[![Circle CI](https://circleci.com/gh/cryptoplay/docker-ubuntu.png?circle-token=35697edcc84351ed5a53038ca8f9b1f2deaa7a2f)](https://circleci.com/gh/cryptoplay/docker-ubuntu/tree/master 'View CI builds')

[![Throughput Graph](https://graphs.waffle.io/cryptoplay/docker-ubuntu/throughput.svg)](https://waffle.io/cryptoplay/docker-ubuntu/metrics)
