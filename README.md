# Basic ERC721 token sample with royalties

This project demonstrates a basic ERC721 token sample with royalties. It comes with a sample contract,  a sample script that deploys that contract which uses NFT Storage service for uploading images to IPFS, and an example of a task implementation, which simply lists the available accounts.


## Setup

- Add metamask account secret key in `ERC721ROYALTIESSAMPLE/.secret` file.

- Add Ropsten or Polygon RPC URL's, minter account address, IPFS API key in .env file.

- Compile Solidity ERC20 contract with below command

    ` npx hardhat compile`

- Deploy ERC20 smart contract with below command

    `node scripts/deploy.js`