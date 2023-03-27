NFTMRI
NFTMRI is a smart contract for creating non-fungible tokens (NFTs) that represent MRI scans. The contract is implemented in Solidity and uses the OpenZeppelin library to provide ERC721 functionality for managing the NFTs.

Getting Started
To get started with using the NFTMRI smart contract, you will need to have access to a Solidity compiler such as Remix, and an Ethereum network for deploying the contract. You can also use an Ethereum development framework such as Truffle or Hardhat to simplify the process of deploying and testing the contract.

Deploying the Contract
To deploy the NFTMRI contract, you can follow these steps:

Copy the code from the NFTMRI.sol file into your Solidity compiler.
Compile the code to generate the bytecode and ABI for the contract.
Deploy the contract to your Ethereum network of choice.
Using the Contract
Once the contract is deployed, you can use the following functions to interact with it:

mintMRI
The mintMRI function allows the owner of the contract to create a new MRI NFT and assign it to a specific address. The function takes two arguments:

to (address): The address that will receive the new NFT.
scanUrl (string): The URL of the MRI scan that the NFT represents.
The function returns the token ID of the new NFT.

getMRI
The getMRI function allows anyone to query information about a specific MRI NFT, including the address of the owner and the scan URL. The function takes one argument:

tokenId (uint256): The ID of the NFT to query.
The function returns a tuple containing the address of the owner and the scan URL.

Contributing
If you find a bug or have a suggestion for improving the NFTMRI contract, please open an issue or pull request on the GitHub repository. Contributions are welcome and appreciated!

License
The NFTMRI contract is available under the MIT License. See the LICENSE file for more information.



