# Moneta Verde cryptocurrency (MCN)


Monetaverde is a cryptonight based cryptocurrency (ticker : MCN)

This is the monetaverde core source code and binary release.

[Main website](https://mcn.green)

[BitcoinTalk main announcement thread](https://bitcointalk.org/index.php?topic=5069658)

[monetaverde-wallet gui (source and binaries)](https://github.com/mcnproject/monetaverde-wallet)


Libraries needed : boost >=1.58

How to compile this :
```
$ git clone https://github.com/mcnproject/monetaverde.git
$ cd monetaverde
$ mkdir build
$ cd build
$ cmake -D STATIC=ON -D CMAKE_BUILD_TYPE=RELEASE ..
$ PORTABLE=1 make
```
## For Building MonetaVerde - MCN - MultiAlgo V 1.0.0  on Ubuntu 18.04

(These are instructions for building on a fresh Ubuntu installation. No other dependencies are required) :
```

$ sudo apt update
$ sudo apt upgrade
$ sudo apt install build-essential
$ sudo apt install libboost-all-dev
$ sudo apt install cmake
$ sudo git clone https://github.com/mcnproject/monetaverde.git
$ cd monetaverde
$ mkdir build
$ cd build
$ cmake ..
$ make
```
