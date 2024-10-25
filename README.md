# Decentralized Voting Application using NextJS

This is a demo application to implement voting in solidity smart contract and backend API in NextJS. 

[Youtube Tutorial](https://youtu.be/qbL-gQDzT0o)


## Architecture

![alt text](https://raw.githubusercontent.com/syedmuhamaddanish/To-Do-List-BlockChain-NextJS/main/to-do-01.jpg)

## Installation

After you cloned the repository, you want to install the packages using

```shell
npm install
```

You first need to compile the contract and upload it to the blockchain network. Go to https://remix.ethereum.org/, and deploy the smart contract on your choice of blockchain. Copy and paste the abi and contract address along with rpc-url of the blockchain network in /Utils/config.js. Also get the private key from your metamask account. 


Once you have done everthing above, simply run the following command to make the server running

```shell
npm run dev
```
