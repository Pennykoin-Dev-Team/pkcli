Pennykoin is a private, secure cryptocurrency forked form digital/dark/ducknote. There was no premine or ICO, all coins are emitted as mining rewards or interest.

_______________________________________________________________________________________
PK has been tested to compile on Windows 8-10 with VS2013, OSX High Sierra, Ubuntu 14-18, Solus, and EL7 ( must add elrepo & epel)

The legacy branch is tweaked to run on VPS (openvz) with very old kernels. If you cannot get it running, please contact jerry on twitter or discord.

for ubuntu:
    apt-get update && apt-get upgrade -y && apt install screen make cmake build-essential libboost-all-dev pkg-config libssl-dev libzmq3-dev libunbound-dev libminiupnpc-dev libldns-dev git nano

for solus: eopkg install libboost-devel cmake make pkg-config gcc libsodium-devel g++ glibc-devel binutils miniupnpc-devel zeromq-devel unbound-devel readline-devel linux-headers

for EL7: yum install cmake boost-devel ( make sure it's the 1.5.3 ver) when installing OS make sure to add development tools

If you have previously installed PK and have the blockchain downloaded, comment out line 27 of cmakelists.txt.

If you successfully get PK to build on other systems, please update this document
