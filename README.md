# Solidity-Create-a-Token

This is a Solidity contract that demonstrates the syntax of a token. This project has public variables that store the details about a coin i.e., Token Name, Token Abbreviation, and Total Supply. 

# Getting Started
To get started, you'll need an Solidity IDE, I've this project on a browser-based IDE Remix. 
Quick Steps: 
Create a new file, write the code, choose a solidity compiler. 

To deploy the contract, you can use any Ethereum development tool such as Remix, Truffle, or Ganache. Once deployed, you can interact with the contract by calling its functions using a web3-enabled client like MetaMask or by writing your own JavaScript or Python script.


# Functions
The contract provides the following two functions:

1) Burn Function
2) Mint Function

This contract has a burn function, it destroys the tokens. The working of Mint functions is exactly oposite to Burn Function. Burn Function take an address and value just like mint function. 
Then it will deduct the value from the total supply and from the balance of the address. Burn Function in this project has a condition to make sure the balance is greater/equal to amount which is supposed to be burned. 

# Authors
Arshdeep Singh
@Asinghhackerzz

# License
This project is licensed under the MIT License.

This is my first project in Solidity and my first repository on GitHub. Thanks to Metacrafters team which helped me in the whole project. 
