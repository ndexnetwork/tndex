----
# nDEX Network | A Blockchain Business Development Platform [ Test Net ] #
[![Docker Stars](https://img.shields.io/docker/stars/ndexnetwork/tndex.svg)](https://hub.docker.com/r/ndexnetwork/tndex?style=flat)
[![Docker Pulls](https://img.shields.io/docker/pulls/ndexnetwork/tndex.svg)](https://hub.docker.com/r/ndexnetwork/tndex?style=flat)
![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/ndexnetwork/tndex?label=nDEX%20%7C%20docker%20build&style=flat)
![GitHub release (latest by date)](https://img.shields.io/github/v/release/ndexnetwork/tndex?style=flat)

----
## What is NDX? ##
NDX is a cryptocurrency to make the world a better place.
See [LICENSE](https://raw.githubusercontent.com/ndexnetwork/tndex/master/.github/LICENSE)

----

### PORTS AND DETAILS
--------------------
Name of Blockchain: nDEX

Coin Symbol: NDX

Coin Supply: 1B

Coin Supply: 900M
-------------------
### Ports
API server port: 6868

Peer port: 6899

Testnet API port: 6876

Testnet peer port: 6898



### Website of the project: [nDEX Network](https://ndexnetwork.com)

### Well known SEED or Web wallets:

https://ndxdaily.npay.life

https://ndxlive.npay.life

https://ndxeco.npay.life

https://ndxworld.npay.life


### Well known SEED/Wallet for testnet:
https://test.npay.life

## ndex-node client is out [get it](https://github.com/ndexnetwork/ndex-node)

### Run in Docker [Easy like 1,2,3 ]
```
1. Install docker : sudo curl -sSL https://get.docker.com/ | sh
2. Install docker-compose & change its permission:  
sudo curl -L https://github.com/docker/compose/releases/download/1.24.1/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
sudo chmod +x /usr/local/bin/docker-compose
3. Finally run:

docker run --name ndex -d \
 --volume nxt_db:/root/.nDEX \
 -p 0.0.0.0:80:6868 \
 --publish 6898:6898 \
 --publish 6876:6876 \
ndexnetwork/ndex


[ No deps no fixer!!!]
```

### Open JDK works FINE!!
### Compile it! ##
----
  - if necessary with: `./compile.sh`
  - you need jdk-8/openjdk-8 as well 

----
### Run it! ##

  - click on the NDX icon, or start from the command line:
  - linux: `./start.sh` or ./run.sh
  - Window: `run.bat`

  - wait for the JavaFX wallet window to open
  - on platforms without JavaFX, open http://localhost:6876/ in a browser

----

## Troubleshooting the NDX Server ##

  - How to Stop the NDX Server?
    - click on NDX Stop icon, or run `./stop.sh`
    - or if started from command line, ctrl+c or close the console window

  - UI Errors or Stacktraces?
    - report on Github

  - Permissions Denied?
    - no spaces and only latin characters in the path to the NRS installation directory
    - known jetty issue

----
### Further Reading ##

  - in this repository:
    - USERS-GUIDE.md
    - DEVELOPERS-GUIDE.md
    - OPERATORS-GUIDE.md
    - In the doc folder

----

```
                               Copyright © 2020 nDEX Network Ltd.
                             Copyright © 2016-2018 Jelurida IP B.V.

```
