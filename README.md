# Web Request Container

A container that outputs the IP addresses of the source and destination. This is very useful for testing a loadbalancer in order to show real requests.

## Supported tags and respective Dockerfile links

* [`latest` (latest/Dockerfile)](https://github.com/kubeskills/web-request/blob/master/Dockerfile)

For more information about this image and its history, please see the relevant manifest file in the [`kubeskills/web-request` GitHub repo](https://github.com/kubeskills/web-request).

## What is ?
[web-request](https://github.com/kubeskills/web-request) is a simple web to show the source and destination IP addresses of the received requests information, written in python.


## How to use this image?
The docker image is auto built at [https://registry.hub.docker.com/u/kubeskills/web-request/](https://registry.hub.docker.com/u/kubeskills/web-request/).


### In Dockerfile
```sh
FROM kubeskills/web-request:latest
```

### Local Run
```sh
$ docker run --rm -it -p 80:80 kubeskills/webrequest:latest
```

## Which image is based on?
The image is based on python:2.7

## What has been changed?
Add the index.py code.
