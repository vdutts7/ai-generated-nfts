# AI Generated NFT Collection

## Overview

I put together a framework to create and mint your own Generative NFT Collection like Bored Ape Yacht Club and CryptoPunks. With this template (steps below), you will be able to:

- Generate thousands of AI images with unique characteristics (also called "properties") via DALL-E
- Upload .jpg metadata to IPFS via Pinata
- Create + deploy basic ERC-721 Smart Contract via RemixIDE using Solidity and existing Ether.js, Web3.js libraries (this may change in the future, please chec OpenZeppelin for most recent templates if encountering errors)
- Bulk mint on OpenSea marketplace as a publicly available NFT collection

<strong>Tools and technologies used:</strong> DALL-E, IPFS, Pinata, RemixIDE, OpenZeppelin, Ether.js, Web3.js, Smart Contracts, Solidity, Hardhat, OpenSea.

<img width="720" alt="r" src="https://user-images.githubusercontent.com/63992417/210648234-5408dc64-6bdf-47fd-9496-73079ed1aa9b.png">


## Steps (NFT collection of size 10 used in example)
1. Create an account here --> https://vanity-eth.tk/
2. Acquire ether via Ropsten test network --> https://faucet.egorfine.com/
3. Make .env file with Ropsten url and private key
4. Deploy to Hardhat network (local dev blockchain) <br />
   npx hardhat run --network localhost scripts/deploy.js
5. Deploy to Ropsten <br />
   npx hardhat run --network ropsten scripts/deploy.js
6. Mint the NFTs at these endpoints (10 total): <br />
    https://ipfs.io/ipfs/QmS416JXfsW8kUJ5fcvabbaeabvd5g1n8pfnkt9Wk4pJLE/1.json
    https://ipfs.io/ipfs/QmS416JXfsW8kUJ5fcvabbaeabvd5g1n8pfnkt9Wk4pJLE/2.json
    https://ipfs.io/ipfs/QmS416JXfsW8kUJ5fcvabbaeabvd5g1n8pfnkt9Wk4pJLE/3.json
    https://ipfs.io/ipfs/QmS416JXfsW8kUJ5fcvabbaeabvd5g1n8pfnkt9Wk4pJLE/4.json
    https://ipfs.io/ipfs/QmS416JXfsW8kUJ5fcvabbaeabvd5g1n8pfnkt9Wk4pJLE/5.json
    https://ipfs.io/ipfs/QmS416JXfsW8kUJ5fcvabbaeabvd5g1n8pfnkt9Wk4pJLE/6.json
    https://ipfs.io/ipfs/QmS416JXfsW8kUJ5fcvabbaeabvd5g1n8pfnkt9Wk4pJLE/7.json
    https://ipfs.io/ipfs/QmS416JXfsW8kUJ5fcvabbaeabvd5g1n8pfnkt9Wk4pJLE/8.json
    https://ipfs.io/ipfs/QmS416JXfsW8kUJ5fcvabbaeabvd5g1n8pfnkt9Wk4pJLE/9.json
    https://ipfs.io/ipfs/QmS416JXfsW8kUJ5fcvabbaeabvd5g1n8pfnkt9Wk4pJLE/10.json
