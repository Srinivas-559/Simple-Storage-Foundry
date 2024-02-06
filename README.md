
# Simple Storage 

The Simple Storage Contract is a basic example of a smart contract written in Solidity for the Ethereum blockchain. It allows users to store and retrieve a single unsigned integer value.


## Deployment

To deploy this project run

```foundry
  forge init 
```


## Running Tests

To run tests, run the following command

```solidity
    forge test 
```

```solidity
    forge compile
```
```solidity
    forge create SimpleStorage --private-key <PRIVATE_KEY>
```


## Environment Variables

To run this project, you will need to add the following environment variables to your .env file

`RPC_URL`

`PRIVATE_KEY`

