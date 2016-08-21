# Example C++ Application using OpenSSL [![Build Status](https://travis-ci.org/ntnu-tdat3020/openssl-example.svg?branch=master)](https://travis-ci.org/ntnu-tdat3020/openssl-example)

## Prerequisites
The C++ IDE [juCi++](https://github.com/cppit/jucipp) should be installed.

## Installing dependencies

### Debian based distributions
`sudo apt-get install libssl-dev`

### Arch Linux based distributions
`sudo pacman -S openssl`

### OS X
`brew install openssl`

## Compiling and running
```sh
git clone https://github.com/ntnu-tdat3020/openssl-example
cd openssl-example
juci .&
```

Choose Compile and Run in the Project menu.

## Running tests

### Alternative 1
First, if you have altered `tests/crypto_test.cpp`, save it.
Then, in a terminal:
```sh
cd build
make
make test
```

### Alternative 2
First, if you have altered `tests/crypto_test.cpp`, save it.
Then, choose Run Command in the juCi++ Project menu, and run the following command:
```sh
cd build && make && make test
```

### Alternative 3
In juCi++, open `tests/crypto_test.cpp`, and choose Compile and Run in the Project menu.
