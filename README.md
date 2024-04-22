# Polygon-Bridge

Welcome to the project guide on deploying an NFT collection to the Ethereum blockchain and bridging it over to Polygon using the Polygon Bridge. This will help to increase the demand for your NFTs and save on gas fees, making your project more accessible and efficient. This README will walk you through the steps to create your NFTs using AI-generated images, deploy them on the Sepolia Ethereum Testnet, and finally bridge them to Polygon Mumbai.

## Project Overview

In this project, you'll:
- Generate a 5-item NFT collection using AI tools like DALLE 2 or Midjourney.
- Store the NFT images on IPFS using pinata.cloud.
- Deploy an ERC721 or ERC1155 smart contract to the Sepolia Ethereum Testnet.
- Map your NFT collection to the Polygon network for better visibility and interaction.
- Use Hardhat scripts to mint and transfer NFTs effectively.
- Test and verify the deployment and transfer on the Polygon Mumbai test network.

## Steps to Follow

### 1. Generate NFT Images
- Use DALLE 2 or Midjourney to create a collection of 5 unique images.
- Save the images and note down the prompts used for each image creation.

### 2. Store Images on IPFS
- Upload your NFT images to IPFS via pinata.cloud to ensure they are securely and permanently stored.

### 3. Smart Contract Deployment
- Deploy an ERC721 or ERC1155 smart contract to the Sepolia Ethereum Testnet.
- Implement a `promptDescription` function in your smart contract to return the prompt used for generating each NFT image.

### 4. Map NFT Collection
- Although not necessary for functionality, you can use the Polygon network token mapper for better visualization and tracking of your NFTs on the blockchain.

### 5. Minting NFTs
- Write a Hardhat script using the ERC721A (if ERC721) optimization for batch minting all your NFTs. This script helps in reducing the gas cost per mint.

### 6. Transfer NFTs to Polygon Mumbai
- Write another Hardhat script to batch transfer all NFTs from Sepolia Ethereum to Polygon Mumbai using the FxPortal Bridge.
- Approve the NFTs for transfer.
- Deposit the NFTs into the bridge.

### 7. Testing and Verification
- Test the `balanceOf` function on Mumbai to ensure that the NFTs have been successfully bridged over.
- Verify that all functionalities are working as expected on both networks.

## Author 
rajadityafaujdar
- - -
