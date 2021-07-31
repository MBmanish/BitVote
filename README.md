## Background
### Why is it bad to build a voting application with centralized application?
 - Votes can change
 - Election rules can change
 
 ### What are the aims of a voting application?
  - Votes should only be counted once.
  - Votes should not change once the voter has voted.
  - The most votes should win.
  
 ### How is a block chain better than a centralized application?
   - Data on the block chain is decentralized and distributed across nodes.
   - Nodes all share the responsibilities of a central server:
      - Each node contains a copy of all the data on the block chain and they work together to maintain the public ledger.
   - A block chain is essentially a network and databased intertwined into one.
   - Code on the block chain can not be changed once deployed.
   
## About the Application
 - Makes use of the Ethereum Block chain network
 - The election is deployed to the Block chain with "Smart Contracts.
 - Smart Contracts can be written in a language called "Solidity".
 - This project consists of a front-end application rendered through the browser and connected to a local block chain.
 
 ## Design of the Application
 - The front end displays 2 sample candidates that can be voted for.
 - The voter selects from a drop down the candidate of their choice.
 - The voter then enters a secure pin.
    - In the real-world application of this project, these pins would be preset and issued to individual voters.
    - The pin authorizes the user to vote with any unused account on the blockchain.
    - The pin can only be used once.
  - The voter then selects the 'Vote' button and a new page loads which allows them to select another button - "View Election Results",
  which displays the updated vote count after the voter would have voted.
  
  ![image](https://user-images.githubusercontent.com/84837582/127730402-0277bd9a-ec60-45e2-8e92-ba12574a133c.jpg)

