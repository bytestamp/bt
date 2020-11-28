# bt
Register files to blockchain.

This is a sample linux script to use ByteStamp webservices.

# Installation

Tested in Ubuntu 20.04

1. Install prerequisites:
- `sudo apt-get install libcryptx-perl jq`

2. install Bitcoin core

- `sudo snap install bitcoin-core`

3. clone the repo

-  `git clone https://github.com/bytestamp/bt.git`

4. make the script executable

- `chmod +x bt/bt`

5. depending on your environment, put the script in your path

- `sudo cp bt/bt /usr/bin`

# Usage

`bt FILEs`

List BlockChain Information about the FILEs
If no file is registered to BlockChain then register FILEs

