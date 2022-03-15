# eth___swap
## Technology Stack & Tools
- Solidity (Writing Smart Contract)
- Javascript (React & Testing)
- [Web3](https://web3js.readthedocs.io/en/v1.7.1/) (Blockchain Interaction)
- [Truffle](https://trufflesuite.com/tutorial/index.html) (Development Framework)

## Requirements For Initial Setup

- Install [NodeJS](https://nodejs.org/en/), should work with any node version below 16.5.0
- Install [Truffle](https://trufflesuite.com/tutorial/index.html)

## Setting Up

### 1. Clone/Download the Repository
### 2. Install Dependencies:
```bash
$ cd eth___swap
$ npm install
```

### 3. Connect development blockchain accounts to Metamask

- Copy private key of the addresses and import to Metamask
- Connect your metamask to Ganache blockchain, network 127.0.0.1:7545.
- If you have not added Ganache to the list of networks on your metamask, open up a browser, click the fox icon, then click the top center dropdown button that lists all the available networks then click add networks. A form should pop up. For the "Network Name" field enter "Ganache". For the "New RPC URL" field enter "http://127.0.0.1:7545". For the chain ID enter "1337". Then click save.

### 4. Migrate Smart Contracts
```bash
truffle migrate
```
### 5. Run Tests
```bash
$ truffle test
```
### 6. Launch Frontend
```bash
$ npm run start
```



