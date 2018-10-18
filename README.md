# Pennykoin

[![Build Status](https://travis-ci.org/Pennykoin/PKCli.svg?branch=master)](https://travis-ci.org/Pennykoin/PKCli)


   Pennykoin is a private, secure cryptocurrency primarily forked form digital/dark/ducknote.  There was no premine or ICO, all coins are emitted as mining rewards or interest.  Pennykoin works like cash, nobody can track your purchases, or see what's in your wallet. But it's easier than cash, it works like an online checking account, including an option to deposit pennykoin and earn interest.
   
   Pennykoin strives to provide a powerful API for websites, apps, and merchants to integrate easily. PKService & PKCli have different APIs, documentation is on the way for both.

The PKCli package contains/compiles 3 binaries. PKNode is the daemon, PKCli is the wallet, and PKService (usually only needed by merchants, pools, or exchanges. is the multi-wallet service usually called walletd similar.

 CLI Development is targeted at embedded or VPS nodes. We target ubuntu 16.04 as the base for this reason. Effort is made to make sure CLI builds on windows, and binaries will be posted. 16 commits ago or so it also compiled out of the box for centos 7 and solus.  There is a minor tweak to get ubuntu 18.04 going, see bionic.md. 
 
  For ubuntu:
  
  sudo apt install screen make cmake build-essential libboost-all-dev pkg-config libssl-dev libzmq3-dev libunbound-dev libsodium-dev libminiupnpc-dev libreadline6-dev libldns-dev
  
  will set up the environment needed. To build just enter "make" in the directory you cloned to.






Not official release, but close beta
