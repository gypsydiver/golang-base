[![Build Status](https://travis-ci.org/gypsydiver/golang-base.svg?branch=master)](https://travis-ci.org/gypsydiver/golang-base)
# golang-base
Base image that includes golang 1.8 and a functional protobuf compiler

Build using:

 `docker build -t <your-org>/<tag> .`

Feel free to delete any packages left in the image in case of not needing them.

Once pushed use it in your Dockerfiles like so:

`FROM <your-org>/golang-base:<tag>`
