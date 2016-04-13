# fping in a container
# 
# Dockerfile will execute fping and any arguments passed.
# Example: docker run -it --rm networkstatic/fping -help
#
FROM alpine:latest

MAINTAINER Brent Salisbury <brent.salisbury@gmail.com>

# build initial cache | install binary | remove cache
RUN apk update && apk add \
	fping \
	&& rm -rf /var/cache/apk/*

ENTRYPOINT ["fping"]
