# Knuth node

Knuth is a high performance implementation of the Bitcoin protocol focused on users requiring extra capacity and resilience. It is a full node software client, but also a development platform. It is designed for:

- Miners and mining pools running competitive operations.
- Exchanges in need of dependable full indexation.
- Companies and businesses with the intention of building applications.
- Developers who want to take their projects to new levels.
- Newcomers taking their first steps in the blockchain ecosystem.

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

https://kth.cash/images/libraries/cpp.svg
