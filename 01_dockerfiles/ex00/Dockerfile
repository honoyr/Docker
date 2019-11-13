FROM alpine

MAINTAINER dgonor <hello world>

RUN apk update && \
    apk upgrade && \
    apk add vim

ENTRYPOINT vim

# How to build it?
# docker build -t ex00 .

# How to run it?
# docker run --rm -ti ex00

# From an alpine image you’ll add to your container your favorite text editor, vim or emacs, that will launch along with your container.