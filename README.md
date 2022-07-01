# NFT Demo

This is heavily based off of [this](https://github.com/fireship-io/web3-nft-dapp-tutorial).

A web3 Dapp which implements ERC721 (NFTs), both minting and gathering them. This uses the Vite frontend tooling.
The computer bois will rise and take over!

## Usage

```
git clone https://github.com/jagger-harris/nftdemo.git
npm install

# first terminal
npx hardhat node

# second terminal
npx hardhat compile
npx hardhat run scripts/deploy.js --network localhost
npm run dev
```

Make sure to replace the contract address in the Home.jsx file with yours!