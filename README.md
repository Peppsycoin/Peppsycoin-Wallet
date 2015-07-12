# Peppsycoin-Wallet
Peppsycoin Wallet

This i a next generation Coin.

NAME            : Peppsycoin

Coin Target     : 30 Sek

Amount per Block: 95  PSY

Block Halfing   : ALL 788400 Blocks  ( 273.75 Day`s ) 

Retarget        : ALL 9.5 Blocks

Total Ammount   : 159 595 959


It is important that you set the connection Nodes.
addnode=5.149.51.217 

Here is an example of the peppsycoin.conf File: Please use the Master Node addnode=5.149.51.217 


rpcuser=?     

rpcpassword=?  

rpcallowip=*.*.*.*             

rpcport=2222   

daemon=1

server=1

testnet=0  

listen=1

gen=0

maxconnections=20     

addnode=5.149.51.217                            


INSTALL INSTRUCTIONS:

LINUX

-->Go to Wallet Path

cd /WalletsPath/Peppsycoin/src/
make -f  makefile.unix USE_UPNP=

-->After

cd ..
qmake "USE_UPNP=-"
make




