# About this Repo

[![Build Status](https://travis-ci.org/wodby/base-php.svg?branch=master)](https://travis-ci.org/wodby/base-php)
[![Docker Pulls](https://img.shields.io/docker/pulls/wodby/base-php.svg)](https://hub.docker.com/r/wodby/base-php)
[![Docker Stars](https://img.shields.io/docker/stars/wodby/base-php.svg)](https://hub.docker.com/r/wodby/base-php)
[![Docker Layers](https://images.microbadger.com/badges/image/wodby/base-php.svg)](https://microbadger.com/images/wodby/base-php)

This repository is a fork of https://github.com/docker-library/php with a few changes:

* We build only Alpine FPM variants
* Built with libressl instead of openssl
* Additional debug variants of images with --enable-debug and non-stripped bins

## Docker Images

* All images are based on Alpine Linux
* Base image: [wodby/alpine](https://github.com/wodby/alpine)
* [Travis CI builds](https://travis-ci.org/wodby/base-php) 
* [Docker Hub](https://hub.docker.com/r/wodby/base-php)

[_(Dockerfile 7.2)_]: https://github.com/wodby/base-php/tree/master/7.2/alpine3.7/fpm/Dockerfile.wodby
[_(Dockerfile 7.1)_]: https://github.com/wodby/base-php/tree/master/7.1/alpine3.7/fpm/Dockerfile.wodby
[_(Dockerfile 7.0)_]: https://github.com/wodby/base-php/tree/master/7.0/alpine3.7/fpm/Dockerfile.wodby
[_(Dockerfile 5.6)_]: https://github.com/wodby/base-php/tree/master/5.6/alpine3.7/fpm/Dockerfile.wodby
[_(Dockerfile 5.3)_]: https://github.com/wodby/base-php/tree/master/5.3/alpine3.4/fpm/Dockerfile.wodby

| Supported tags and respective `Dockerfile` links | PHP    | Alpine |
| ------------------------------------------------ | ------ | ------ |
| `7`, `7.2.2`, `latest` [_(Dockerfile 7.2)_]      | 7.2.2  | 3.7    |
| `7.1.14` [_(Dockerfile 7.1)_]                    | 7.1.14 | 3.7    |
| `7.0.27` [_(Dockerfile 7.0)_]                    | 7.0.27 | 3.7    |
| `5`, `5.6.33` [_(Dockerfile 5.6)_]               | 5.6.33 | 3.7    |
| `5.3.29` [_(Dockerfile 5.3)_]                    | 5.3.29 | 3.4    |
| `7-debug`, `7.2.2-debug` [_(Dockerfile 7.2)_]    | 7.2.2  | 3.7    |
| `7.1.14-debug` [_(Dockerfile 7.1)_]              | 7.1.14 | 3.7    |
| `7.0.27-debug` [_(Dockerfile 7.0)_]              | 7.0.27 | 3.7    |
| `5-debug`, `5.6.33-debug` [_(Dockerfile 5.6)_]   | 5.6.33 | 3.7    |
