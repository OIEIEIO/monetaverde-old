![](https://github.com/OIEIEIO/monetaverde-images/blob/master/watermark.png) 

MonetaVerde’s blockchain was rebased and released in April 2019. Recognizing the various challenges and competition between cryptocurrencies we decided to set ourself in a different light with our unique approach to becoming the very first Cryptonote multi-algorithm proof of work (PoW) blockchain. This approach has put us in a position where we can always grow in a co-operative manner within the digital currency world. 

We can confirm transactions by merge mining with over 100 different cryptocurrencies so far. 

We use a unique algorithm to increase block reward with difficulty change and keep miners motivation.
Our ability to merge with so my coins puts us in a rather secure and stable environment.

* First Block: June 17, 2014 
* Money Supply: Infinite
* Block Reward: Ascending with difficulty
* Block Maturity: 60 seconds
* Block Confirmation: Proof of Work
* Current Circulation: approximately 75,000,000 (as of September 2019)

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

Monetaverde is a cryptonote based blockchain and cryptocurrency (ticker : MCN)

Instructions on how to build it.

### Dependencies 

Libraries needed : boost >=1.58, | libboost-all-dev | build-essential | cmake

How to compile this :
```
$ git clone https://github.com/mcnproject/monetaverde.git
$ cd monetaverde
$ mkdir build
$ cd build
$ cmake -D STATIC=ON -D CMAKE_BUILD_TYPE=RELEASE ..
$ PORTABLE=1 make
```
## For Building MonetaVerde - MCN - MultiAlgo V 1.0.1  on Ubuntu 18.04

(These are instructions for building on a fresh Ubuntu installation. No other dependencies are required) :
```

$ sudo apt update
$ sudo apt upgrade 
$ sudo apt install build-essential
$ sudo apt install libboost-all-dev
$ sudo apt install cmake
$ sudo git clone https://github.com/OIEIEIO/monetaverde.git
$ cd monetaverde
$ mkdir build
$ cd build
$ cmake ..
$ make
```
