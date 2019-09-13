# Moneta Verde cryptocurrency (MCN)


Monetaverde is a cryptonight based cryptocurrency (ticker : MCN)

This is the monetaverde core source code and binary release.

[Main website](https://mcn.green)

[Block Explorer](https://explorer.mcn.green)

[Paper wallet](https://mcn.green/paperwallet-generator.html)

[Discord](https://discord.gg/ExaXHPt)

[Telegram](https://t.me/joinchat/J345qUOVKPPtsJQgiLbwVQ)

[Twitter](https://twitter.com/MonetaVerde)

[BitcoinTalk main announcement thread](https://bitcointalk.org/index.php?topic=5069658)

[Reddit](https://www.reddit.com/r/monetaverdeMCN)

[Facebook](https://www.facebook.com/Monetaverde)

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
