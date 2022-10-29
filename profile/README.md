# Knuth node

Knuth is a high performance implementation of the Bitcoin protocol focused on users requiring extra capacity and resilience. It is a full node software client, but also a development platform. It is designed for:

- Miners and mining pools running competitive operations.
- Exchanges in need of dependable full indexation.
- Companies and businesses with the intention of building applications.
- Developers who want to take their projects to new levels.
- Newcomers taking their first steps in the blockchain ecosystem.

## Releases

Node executable
C++ Library
C Library <a target="_blank" href="https://github.com/k-nuth/c-api/releases">![Github Releases][badge.release]</a>

## Getting Started

Install and run Knuth is very easy, you must follow these instructions.

1. Install and configure the Knuth build helper:

```
$ pip install kthbuild --user --upgrade

$ conan config install https://github.com/k-nuth/ci-utils/raw/master/conan/config.zip

# Just for Linux

$ conan profile update settings.compiler.libcxx=libstdc++11 default
```

2. Install the node executable:

```
$ conan install kth/0.X@kth/stable --update
```

3. Run the node:

```
# Initialize the database

$ ./kth -i

# Run the node

$ ./kth
```

## Libraries

<a href="https://github.com/k-nuth/node"><img alt="C++" src="https://kth.cash/images/libraries/cpp.svg" width="150" height="150" /></a>
<a href="https://github.com/k-nuth/c-api"><img alt="C++" src="https://kth.cash/images/libraries/c.svg" width="150" height="150" /></a>
<a href="https://github.com/k-nuth/cs-api"><img alt="C++" src="https://kth.cash/images/libraries/csharp.svg" width="150" height="150" /></a>
<a href="https://github.com/k-nuth/js-api"><img alt="C++" src="https://kth.cash/images/libraries/javascript.svg" width="150" height="150" /></a>
<a href="https://github.com/k-nuth/js-api"><img alt="C++" src="https://kth.cash/images/libraries/typescript.svg" width="150" height="150" /></a>
<a href="https://github.com/k-nuth/py-api"><img alt="C++" src="https://kth.cash/images/libraries/python.svg" width="150" height="150" /></a>


## Features

Knuth is characterized by its modular architecture and beautiful code. It has the intention to facilitate adoption and collaboration in the evolution of a diverse ecosystem. We want our code to be interactive, reusable and reliable, easy to read and easy to debug. Some of our features are:

### Development platform

Knuth is a full node implementation, but also a development platform. Its core is written in C++. On top of it, several libraries and modules, written in several programming languages, are provided and can be used as a basis for building applications.

### Build system

Our build system is designed to automatically detect processors’ microarchitecture and optimize the binary generated at build time.

### Processes and industry standards

Knuth has the best processes and standards available. It is written in C++ and uses libraries such as Abseil, Boost, GMP, ICU, among others. In terms of toolchains, Knuth uses GCC, Clang, MSVC, CMake, Conan, clang-tidy, and clang-format.

### Cross-Platform

Knuth is a cross-platform solution. It can be used in any computer architecture and operating system. It only requires a 64-bit machine. Its code can be compiled and natively used on Linux, Windows, macOS, FreeBSD, and others with no fuzz.

### Database modes

Designed to offer a high level of specialization for particular use cases, Knuth node can be initialized under 3 different database modes at installation time: normal, pruned and full-indexed. An orthogonal read-only mode is provided for scaling capabilities.

### Modularization

Knuth is built following a completely modular architecture. Each module is a library that can be used independently or together with other libraries. This adds a neat and readable code organization that follows the single-responsibility principle. Any protocol change can be introduced in Knuth much faster and efficiently.


## Donation

Knuth is a community backed project developed. Donations received will be used to subsidize development costs for general maintenance and support of our implementation.

Your contributions are greatly appreciated!

`bitcoincash:qrlgfg2qkj3na2x9k7frvcmv06ljx5xlnuuwx95zfn`

