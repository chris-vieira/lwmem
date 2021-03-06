# Lightweight dynamic memory manager

<h3><a href="http://docs.majerle.eu/projects/lwmem">Documentation</a></h3>

## Features

* Written in ANSI C99, compatible with ``size_t`` for size data types
* Implements standard C library functions for memory allocation, malloc, calloc, realloc and free
* Uses *first-fit* algorithm to search free block
* Supports different memory regions to allow use of fragmented memories
* Suitable for embedded applications with fragmented memories
* Suitable for automotive applications
* Supports advanced free/realloc algorithms to optimize memory usage
* Operating system ready, thread-safe API
* User friendly MIT license

## Contribute

Fresh contributions are always welcome. Simple instructions to proceed::

1. Fork Github repository
2. Respect [C style & coding rules](https://github.com/MaJerle/c-code-style) used by the library
3. Create a pull request to develop branch with new features or bug fixes

Alternatively you may:

1. Report a bug
2. Ask for a feature request
