# Hscoin [HSC]
http://www.euro-hash.eu/

![HSCoin](http://www.euro-hash.eu/images/hsc_256x256x32.png)

## What is HSCoin
Hscoin is like Bitcoin, but based on Litecoin


## License 
HSCoin is released under the terms of the MIT license. See [COPYING](COPYING)
for more information or see http://opensource.org/licenses/MIT.

## Development and contributions - omg developers
Developers work in their own trees, then submit pull requests when they think
their feature or bug fix is ready.

## Very Much Frequently Asked Questions

### How much HSC can exist?
Total of 100,000,000,000 much coins

### BASE
Scrypt Proof of Work

1 Minute Block Targets, 4 Hour Diff Readjustments

Special reward system: Random block rewards

1-100,000: 0-1,000,000 Hscoin Reward

100,001 - 200,000: 0-500,000 Hscoin Reward

200,001- 300,000: 0-250,000 Hscoin Reward

300,001 - 400,000: 0-125,000 Hscoin Reward

400,001 - 500,000: 0-62,500 Hscoin Reward

500,001 - 600,000: 0-31,250 Hscoin Reward

600,000+ - 10,000 Reward (flat)

### Wow plz make hscoind

    sudo apt-get install build-essential \
                         libssl-dev \
                         libdb5.1++-dev \
                         libboost-all-dev \
                         libqrencode-dev \
                         libminiupnpc-dev

    cd src/
    make -f makefile.unix USE_UPNP=1 USE_IPV6=1 USE_QRCODE=1

### ports
RPC 9392
P2P 9393

![](http://www.euro-hash.eu)
