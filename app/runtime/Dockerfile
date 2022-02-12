# image info
ARG AUTHOR_NAME
ARG AUTHOR_EMAIL
ARG VERSION

FROM alpine:$VERSION
LABEL author=$AUTHOR_NAME email=${AUTHOR_EMAIL} version=$VERSION
# change apk source to ali
RUN sed -i 's/dl-cdn.alpinelinux.org/mirrors.aliyun.com/g' /etc/apk/repositories && apk update && apk upgrade
# intstall git build-base opencv-dev
RUN apk add --no-cache opencv

