# Cranky Coin

[![Build Status](https://travis-ci.org/cranklin/crankycoin.svg?branch=master)](https://travis-ci.org/cranklin/crankycoin)

Cranky Coin is a simple blockchain, cryptocurrency, wallet implementation

It demonstrates the core concepts of a cryptocurrency system: wallets, transactions, blocks, nodes, and mining.

## Features

Wallets: Create wallets with public/private key pairs.

Transactions: Sign and broadcast transactions using your wallet.

Blockchain: A simple chain of blocks containing verified transactions.

Consensus: Proof-of-work based mining.

Nodes: Run a full node to verify blocks, relay transactions, and maintain the chain.

Mining: Start/stop a mining process to secure the network and earn rewards.

## Getting Started

```
# apt install python3-pip
# pip3 install virtualenv
# virtualenv -p python3 venv
# . venv/bin/activate
# pip install -r requirements.txt
# pip install -r requirements-dev.txt
```

**Generating a wallet**

```
# python run.py client
Cranky Coin (CRNK) wallet > publickey
```

_copy your public key_

```
Cranky Coin (CRNK) wallet > privatekey
```

_copy your private key_

**Running a full node**

```
Cranky Coin (CRNK) wallet > quit
# python ./tools/encrypt.py
```

_enter a secure passphrase_

```
Choose a passphrase:
Re-enter your passphrase:
```

_enter your private key_

```
Secret:
Encrypted private key:
```

_copy your encrypted private key_

_edit config/config.yaml and populate the fields in the `user` section_

```
# python run.py full
Cranky Coin (CRNK) full node > help
```

**Running a mining node**

```
Cranky Coin (CRNK) full node > mine start
Cranky Coin (CRNK) full node > mine stop
```
