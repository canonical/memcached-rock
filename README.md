# Memcached Rock

A distroless-like memcached image based on Ubuntu. 

## Chiseled image

This image was created with [Chisel](https://documentation.ubuntu.com/chisel) to reduce the content of this image to only the essentials. This creates a more compact image with a smaller overall attack surface. Details on the content of this image can be found under the `memcached_bins` slice(s) in the [chisel-releases](https://github.com/canonical/chisel-releases)
repository.

## Available versions

* [memcached-1.6 (Ubuntu 26.04)](./memcached/1.6-26.04/rockcraft.yaml)