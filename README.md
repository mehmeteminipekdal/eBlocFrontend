# Starting Project

```shell
npm install --save-dev ethers
sudo chown -R mehmeteminipekdal:staff . -if there is an access/permission error-
npm start
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
