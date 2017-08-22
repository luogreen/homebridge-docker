# Homebridge-Docker

Docker image for Homebrigde
This project only builds a docker image, please do not report problems with homebridge but look into the homebridge project: For details see https://github.com/nfarina/homebridge

As said, this is simply wrapping the source in a runnable Docker image for everyone that cannot install the dev environment on his machine or everyone that wants a simple containerized solution.
If you intend to run this docker image on a Synology NAS, read this documentation:
http://chris.brandlehner.at/Brandlehner/cab_blog.nsf/d6plinks/CBRR-A6XQUY

## Run

```shell
docker run -d --restart --net=host --name=homebridge -p 51826:51826 luogreen/homebridge
```



