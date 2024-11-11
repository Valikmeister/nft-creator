# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a Hardhat Ignition module that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat ignition deploy ./ignition/modules/Lock.ts
```




## Dependencies

Pinata - Cloud IPFS storage for NFT ( custom solution can also be used ), Image storage 
- Docs: https://docs.pinata.cloud/quickstart


Infura - Faucet for ETH testnet and testnet nodes, to simulate mainnet tests(Alchemy Faucet is also a good alternative)

- Faucet: https://www.infura.io/faucet/sepolia?__cf_chl_f_tk=VOs4x46qHkYmNH_3K3ifIlVEEGBdd9SDTky5AJE9Mfo-1731332513-1.0.1.1-iFX262pLYYgAKgi3CAPe_sHzhSiDRp_EiqtauOAH_D0


HardHat - ETH developer environment

- Docs: https://hardhat.org/docs


OpenSea - NFT market 
 - List NFT's: https://docs.opensea.io/docs/list-an-nft-for-sale




 ## Requirements

 - Create a CLI tool capable of creating and minting NFT contracts and upload them to OpenSea Marketplace

 - Manage minted NFT's and un-Minted contracts, create option to allow addresses for pre-ownership of contract 

 - (Future) Try Deno Runtime to package CLI into a standalone Windows exe