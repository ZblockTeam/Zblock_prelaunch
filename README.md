Zblock 1.0.0
==============

What is Zblock?
----------------
Zblock is a Zcash/Zclassic based Blockchain-as-a-Service cryptocurrency.

Zblock is an anonymous, distributed, fast and crypto-secured ledger built on top of samrt blockchain.

Zblock is free and opensource, now and forever.


Get dependencies:
```{r, engine='bash'}

sudo apt-get install \
      build-essential pkg-config libc6-dev m4 g++-multilib \
      autoconf libtool ncurses-dev unzip git python \
      zlib1g-dev wget bsdmainutils automake
```

Install
```{r, engine='bash'}
# Build
./zcutil/build.sh -j$(nproc)
# fetch key
./zcutil/fetch-params.sh
# Run
./src/zcashd
```


About
--------------

[Zblock](http://Zblock.org/) is an implementation of the "Zerocash" protocol.
Based on Bitcoin's code, it intends to offer a far higher standard of privacy
through a sophisticated zero-knowledge proving scheme that preserves
confidentiality of transaction metadata. Technical details are available
in the Zcash [Protocol Specification](https://github.com/zcash/zips/raw/master/protocol/protocol.pdf).

This software is the Zblock client. It downloads and stores the entire history
of Zblock transactions; depending on the speed of your computer and network
connection, the synchronization process could take a day or more once the
blockchain has reached a significant size.

Security Warnings
-----------------

See important security warnings in
[doc/security-warnings.md](doc/security-warnings.md).

**Zblock is unfinished and highly experimental.** Use at your own risk.

Where do I begin?
-----------------

Building
--------

Complete source will be released after crowdfunding sale. This source code miss the chainparams file and frontend folders to avoid code exploitation before the official launch but at the same time to give proof of existence of code.

License
-------

For license information see the file [COPYING](COPYING).
