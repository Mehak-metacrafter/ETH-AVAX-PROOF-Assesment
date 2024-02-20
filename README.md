# Simple Solidity Smart Contract

This is a simple Solidity smart contract for managing ownership..

## Description

This Solidity smart contract allows for ownership management, where the owner can perform certain actions exclusively. It includes functions to check if the caller is the owner, restrict access to certain functions to only the owner, and ensure that only the owner can call specific functions.
## Getting Started

### Installing

You can obtain the smart contract by either copying the provided Solidity code or downloading it from the repository.

### Executing program

To deploy and interact with the contract, follow these steps:

1. Navigate to the directory where the contract file (Ownership.sol) is located.

2.Compile the contract using your Solidity compiler.

3.Deploy the compiled contract to your preferred blockchain network.

4.Interact with the deployed contract using a tool like Remix, or write scripts using Web3.js or ethers.js to interact programmatically.
```
//Only owner can call
    function onlyOwner() public view 
    {
        require(msg.sender == owner, "Only the owner can call this function.");
    }
```

![image](https://github.com/Mehak-metacrafter/ETH-AVAX-PROOF-Assesment1/assets/155759527/19ec84ad-ad86-4882-ae14-da1d19cf8ce9)


## Authors

[Mehak Thakur] [mehakthakur051003@gmail.com]




## License

This project is licensed under the MIT License - see the LICENSE.md file for details
