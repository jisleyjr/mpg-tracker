Created from the template https://github.com/XamHans/React-Solidity-Typescript-Starter. Comes as a monorepo for your next fullstack dApp Development. This will be your tools:
:pager: React + Vite + Typescript
 :page_with_curl: Solidity + Hardhat + Typescript

Typescript is integrated in the frontend as well in the smart contract part. This gives you a HUGE advantage, why? Because you can use types from the smart contract in your frontend part ( with the help of typechain https://github.com/dethcrypto/TypeChain). 


## How to start

### Backend
pre: cd into /backend

0) install hardhat locally ---> npm install --save-dev hardhat
1) start local testnet ---> npm run testnet
2) Compile contracts ---> npm run compile
3) Test contracts --->     npm run test
4) Deploy contracts --->   npm run deploy

### Frontend
pre: cd into /frontend

1) Install dependencies ---> npm install
2) start frontend ---> npm run dev
3) build --> npm run build
