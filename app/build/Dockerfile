# image info
ARG AUTHOR_NAME
ARG AUTHOR_EMAIL
ARG VERSION

FROM golang:alpine$VERSION
LABEL author=$AUTHOR_NAME email=${AUTHOR_EMAIL} version=$VERSION
# intstall git build-base opencv-dev
RUN apk add --no-cache opencv-dev

