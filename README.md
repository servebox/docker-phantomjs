# PhantomJS image

PhantomJS image built from sources (2.0.0) on Ubuntu 14.04.

## Get the image

The image can be found on the Docker
Hub(https://registry.hub.docker.com/u/servebox/phantomjs/).

```
docker pull servebox/phantomjs:latest
```
## Usage

You may run it on the command line:

```
docker run -t servebox/phantomjs phantomjs --version
```

But you'll probably want to use it as a base image:

```
FROM servebox/phantomjs:latest
```

## Source

[Github Repository](https://github.com/servebox/docker-phantomjs)
