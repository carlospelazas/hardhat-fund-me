# Fund Contract with Solidity and Javascript

FundMe, is a solidity program which is able to get funds from other users onto the contract and withdraw them
The deployments are done with javascript, and we implemented a Mock for running tests on the local hardhat network or a localhost.
I used the testnet goerli for this project and this is my first Smart Contract program, as well as my first repo on github!

Try running some of the following tasks:

```shell
yarn test (hardhat network)
yarn test --network goerli (goerli network, check etherscan)

yarn hardhat node (localhost)
yarn hardhat run scripts/fund.js
yarn hardhat run scripts/withdraw.js
```
