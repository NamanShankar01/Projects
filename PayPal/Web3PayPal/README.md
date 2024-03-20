# SMART CONTRACT

The ###NS_Pay### is a decentralized financial platform built on the principles of Web3 technology. Inspired by the popular payment gateway PayPal, this application aims to provide users with a secure, transparent, and efficient system for conducting online transactions.

Try running the following commands to deploy the smart contract and see its functionality on [Mumbai_PolygonScan](https://mumbai.polygonscan.com/):

```shell
npm i -D hardhat 
npx hardhat init
npm i -D dotenv
npm i -D @nomiclabs/hardhat-waffle
npm i -D @nomiclabs/hardhat-etherscan
npx hardhat clean
npx hardhat compile
npx hardhat run scripts/deploy.js --network mumbai
```
Also, create an ".env" file and add the following in it :

POLYGON_MUMBAI = 'https://polygon-mumbai-bor-rpc.publicnode.com'
PRIVATE_KEY = '[your account private key]' 
API_KEY = '[your API key of PolygonScan]'
