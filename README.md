# Challenge-21

## Background
After waiting for years and passing several tests, you were selected by the Martian Aerospace Agency to be part of the first human colony on Mars. As a prominent fintech professional, you were chosen to lead a project to develop a monetary system for the new Mars colony. You have decided to base this new monetary system on blockchain technology, and to define a new cryptocurrency called KaseiCoin. (“Kasei” means “Mars” in Japanese.)

KaseiCoin will be a fungible token that is ERC-20 compliant. You will launch a crowdsale that will allow people who are moving to Mars to convert their earthling money to KaseiCoin.

$$ What You're Creating
You will create a fungible token that is ERC-20 compliant and that will be minted by using a Crowdsale contract from the OpenZeppelin Solidity library.

The crowdsale contract that you create will manage the entire crowdsale process, allowing users to send ether to the contract and in return receive KAI, or KaseiCoin tokens. Your contract will mint the tokens automatically and distribute them to buyers in one transaction.

Note that the starter files that are provided for this Challenge contain a pragma for Solidity version 0.5.5. You will use the starter files to do the following:

  1. Create the KaseiCoin token contract.

  2. Create the KaseiCoin crowdsale contract.

  3. Create the KaseiCoin deployer contract.

  4. Perform a real-world, pre-production test of your crowdsale. In order to do so, you will deploy the crowdsale to a local blockchain by using Remix, MetaMask, and Ganache.

  5. Record a short video or take several screenshots that show the deployed contract in action.

  6. Optional: Use OpenZeppelin to extend the functionality of your crowdsale contract by adding time restrictions, refund capabilities, and a cap for the number of tokens that may be created.

## Evaluation Evidence

  1. KaseiCoin Token Contract: 
  ![KaseiCoin](https://user-images.githubusercontent.com/103230949/190037604-62746ce8-acb9-4c52-938a-58d7cd317233.png)
  
  ![KaseiCoin_Compile_0 5 5](https://user-images.githubusercontent.com/103230949/190037456-bb41b098-5d64-44d7-b1e7-d8c9d23cd761.png)

  2. KaseiCoin Crowdsale Contract:
  ![KaseiCoinCrowdsale](https://user-images.githubusercontent.com/103230949/190037582-9f2bc0db-f9a9-4a3a-a88b-53e8cf898350.png)
  
  ![KaseiCoinCrowdsale_Compile_0 5 5](https://user-images.githubusercontent.com/103230949/190037494-1e25d6ce-8fe3-481d-920e-b669d191bd66.png)

  3. KaseiCoin Deployer Contract:
  
  ![KaseiCoinCrowdsaleDeployer](https://user-images.githubusercontent.com/103230949/190037534-4ad66828-7d1b-464b-a639-b2b2532d0ff6.png)
  

  4. Deployment of the Crowdsale Contract:

![KaseiCoinCrowdsale_Deploy_Transact_Metamask](https://user-images.githubusercontent.com/103230949/190037866-c4163aea-f40d-41a7-9110-9657f659c4ce.png)

![KaseiCoinCrowdsale_Deploy_Transact_Metamask_Account4](https://user-images.githubusercontent.com/103230949/190037868-d685684f-1de0-460e-93fa-a38625625e10.png)

