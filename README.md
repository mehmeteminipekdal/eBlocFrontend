# Attention
This is a frontend page for contracts deployed on Sepolia test-network. Thus, anyone shall select his/her Sepolia wallet from Metamask.
Change the contract addresses in eBloc.js with your contract addresses and use your own abi and functions.
If you wish to connect other test networks, change your Metamask wallet to other networks and again update the contract info as stated above.

# Starting Project

```shell
npm install --save-dev ethers
sudo chown -R mehmeteminipekdal:staff . -if there is an access/permission error-
npm start
```
If a port is stuck
```shell
sudo lsof -i :3000     
```
# Installing IPFS
```shell
brew install ipfs
ipfs daemon
ipfs add -r ./source_code  // ipfs add -r .                        
ipfs ls QmX7c5QNeWUkmjsEw18sJ7hHCJibGnSDxDfKhajCT2iPxZ
```
Other related commands
```shell
ipfs cat QmX2U3gBqmUNSceWb6HiYrjc9d2raF5iPMY5p38yHot6Dk
```

# Sample Hardhat Project

This project demonstrates a basic Hardhat use case. It comes with a sample contract, a test for that contract, and a script that deploys that contract.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
