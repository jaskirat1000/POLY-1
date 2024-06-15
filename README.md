# POLY-1

## NFT Collection Deployment and Bridging Project

## Project Overview
This project demonstrates the deployment of a 5-item NFT collection using DALLE 2, storage on IPFS via Pinata, deployment on the Goerli Ethereum Testnet as ERC721 tokens, mapping to Polygon Mumbai network, and bridging using the FxPortal Bridge.

## Setup Instructions
1. Clone this repository.
2. Install dependencies with `npm install`.
3. Configure your environment variables for Ethereum and Polygon networks.
4. Ensure you have an IPFS API key from Pinata.

## Deployment Steps
1. **NFT Generation**: Generate 5 unique items using DALLE 2.
2. **IPFS Storage**: Upload images and metadata JSON files to IPFS via Pinata.
3. **Contract Deployment**: Deploy ERC721 contract on Goerli Testnet.
4. **Mapping to Polygon**: Use Polygon token mapper to map ERC721 contract.
5. **Minting NFTs**: Batch mint all NFTs using Hardhat script.
6. **Transfer to Polygon**: Transfer NFTs from Goerli to Polygon Mumbai using FxPortal Bridge.
7. **Testing**: Verify NFT balance on Polygon Mumbai network.

## Scripts
- **Minting Script**: `scripts/mint.js` - Script to batch mint NFTs.
- **Transfer Script**: `scripts/transfer.js` - Script to transfer NFTs to Polygon.

## Usage
1. **Mint NFTs**: Run `npx hardhat run scripts/mint.js` after configuring.
2. **Transfer to Polygon**: Run `npx hardhat run scripts/transfer.js` after approval.

## Troubleshooting
- If facing issues with IPFS upload, check API key permissions.
- For contract deployment failures, verify network configurations.
- Ensure proper bridging steps for Polygon transfers.

## Resources
- [DALLE 2 Documentation](link-to-dalle-docs)
- [IPFS Pinata Documentation](link-to-pinata-docs)
- [Hardhat Documentation](link-to-hardhat-docs)
- [Polygon FxPortal Bridge](link-to-polygon-bridge-docs)

## License
This project is licensed under the MIT License - see the LICENSE file for details.
- - -
