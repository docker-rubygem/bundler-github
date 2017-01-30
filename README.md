[![Docker pulls](https://img.shields.io/docker/pulls/rubygem/bundler-github.svg)](https://hub.docker.com/r/rubygem/bundler-github/)
[![Docker Build](https://img.shields.io/docker/automated/rubygem/bundler-github.svg)](https://hub.docker.com/r/rubygem/bundler-github/)
[![Latest Tag](https://img.shields.io/github/tag/docker-rubygem/bundler-github.svg)](https://hub.docker.com/r/rubygem/bundler-github/)
[![Gem Downloads](https://img.shields.io/gem/dt/bundler-github.svg)](https://rubygems.org/gems/bundler-github/)
# bundler-github

Auto-Generated Docker image for bundler-github to allow simple usage without installation.
It is in sync with the original gem.

This allows to use a specific version of your favorite gem and ensures that this image will be supported in future.
The image is generated automatically from a github repository by Docker Hub.
This ensures that you exactly know what is in the image and what not.

It lets you use Ruby Tools without the need to install ruby on your machine.

## Usage

Usage via file system:

`docker run -v $(pwd):/work -ti docker-gems/bundler-github`

Usage via Pipe:

`echo "test" | docker run -ti docker-gems/bundler-github`

It depends on your specific use case how your want to use it.

### Add Customization

For extension, it could be used as base image.

So instead of struggeling with the installation of a gem, just write

`FROM docker-gems/bundler-github`

Then add the customization.

## References

 - [Overview over other rubygem docker images](https://github.com/thinkbot/docker-rubygem)
 - [Gem](https://rubygems.org/gems/bundler-github/)
