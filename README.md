# MN-setup-guide


1. Open the core wallet and sync it

Encrypt the wallet (restart wallet)

Backup wallet

Unlock wallet

create recieve address with label
settings > multisend 
 - percentage - 100
 - address - newley generated staking
 - click add
 - click activate
 - click view

tools > debug window

`getnewaddress name`

send exact MN collateral amount to the genereate address.

wait for 2 confirmations

get transaction ID

in tools > debug console

`masternode outputs`

find tx ID and cross reference outputs

`masternode genkey`

Tools > MasterNode Conf File

servername ip:port genkey txid outputid



