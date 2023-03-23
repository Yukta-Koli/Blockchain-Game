# Blockchain-Game
Memory-Tokens   => Game using Blockchain

![Screenshot (256)](https://user-images.githubusercontent.com/84383932/227163055-7c7bd521-b598-4dd3-8023-638fc40bdeaa.png)




Notes while running the game:

1) Make sure Ganache workspace is on.
2) Create Ganache Network in Metamask and import account from Ganache using private key.
3) Connect the ganache account to metamask.



Run following commands in terminal:
1) To clone git repository.
=>  git clone -b master https://github.com/Yukta-Koli/Blockchain-Game blockchain_game

2) TO install all the dependencies.
=> npm install

3) To deploy migrations OR to put smart contracts on blockchain.
=> truffle migrate --reset

4) To test the solidity code if correct
=> truffle test

5) To run the server.
=> npm run start



To change or create a new account of Ganache in MetaMask do the following steps:
1) Import another account in Ganache Network (in MetaMask) using private key fron Ganache workspace and connect it.
2) In terminal run following commands to reset the account connected (to deploy smart contracts on blockchain).
=> truffle migrate --reset
=> npm run start



Installations Needed:
1) Ganache
2) Metamask
3) React js
4) Node js



Create Ganache Network on MetaMask:
1) Add Network Manually
2) 1. Network Name: Ganache
   2. Network RPC URL: use RPC Server URL from Ganache (e.g. => HTTP://127.0.0.1:7545)
   3. Chain ID: 1337 (It is default ID of Ganache)
3) Save the Network 

