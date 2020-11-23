FROM golang:1.15.5-alpine
ENV GOPATH $GOPATH:/go/src
RUN apk update && \
    apk add --update git && \
    rm -rf /var/cache/apk/*
