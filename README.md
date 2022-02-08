## Ethereum Dapp for Tracking Items through Supply Chain(Udacity)

#### In this dapp, there are 4 roles: farmer, distriutor, retailer and consumer. Here the farmer harvests, processes, packs and sells coffee beans to distributor.The distributor buys and ships them to retailer. Finally, retailer receives them and consumer purchases the coffee beans. Here roles contract in accesscontrol is used to add, remove role's access to contracts.(FarmerRole.sol, DistributorRole.sol, RetailerRole.sol, ConsumerRole.sol)

#### Activity Diagram

![truffle test](Uml/Activitydiagram.png)

#### Sequence Diagram

![truffle test](Uml/Sequencediagram.png)

#### State Diagram

![truffle test](Uml/Statediagram.png)

#### Class Diagram

![truffle test](Uml/Classdiagram.png)

#### Run the Dapp
1. Truffle version used in this project:Truffle v5.4.18, Solidity v0.5.16, Node v14.17.5 and Web3.js v1.5.3. And to install Truffle run command
  ```bash
    npm install -g truffle 
  ```
2. Make sure you have Infura account, MetaMask installed, Ganache cli installed and ether in Rinkeby account

3. Clone the repository and run the following
 ```bash
    cd project-6
    npm init and npm install
    npm install web3 
    npm install --save truffle-hdwallet-provider@1.0.17
 ```
4. Launch ganache :
 ```bash
    ganache-cli -m "spirit supply whale amount human item harsh scare congress discover talent hamster" 
 ```
5. Your terminal should look something like this:

![truffle test](Uml/ganache-cli.png)

6. In a separate window run Truffle commands
 ```bash
    truffle compile
    truffle migrate
    truffle test
 ```   

![truffle test](Uml/truffle-test.png)

7. Make sure Metamask is enabled, set Rinkeby network and set infurakey to your Infura Rinkeby projectId
  ```bash
    truffle migrate --reset --network rinkeby
  ```
![truffle test](Uml/truffle-rinkeby1.png)

![truffle test](Uml/truffle-rinkeby2.png)

![truffle test](Uml/truffle-rinkeby3.png)

![truffle test](Uml/truffle-rinkeby4.png)

8. To run the Frontend:
 ```bash
    cd app
    npm run dev
 ```
![truffle test](Uml/Deploy.png)

9. Frontend Transaction history

![truffle test](Uml/TransactionHistory.png)

#### TransactionID and Contract Address
#### TransactionID : 0x805c300911e5fd14f4dd8d690d1374730141e012c74e5afd7d816223dc78af99
#### Contract Address : 0xBDcFEF40D4Af26Be2aCddfe8E3125bc3B852E3F0 
