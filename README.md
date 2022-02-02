# eth-commands

[] Follow the same process of week 1
[x] start a hardhat project
[x] write s.contract
[x] compile s. contract => npx hardhat compile
[x] Configuring Deploy S. Contract
=> [x] Get some Matic
=> [x] Configure module.exports in hardhat.config.js
==> [x] Set up polygon? provider (alchemyapi.io)
==> [x] Add own account private key
===> Who is reading the content of hardhat.config.js?
[] Deploy S. Contract
=> [x] creating deploy.js
=> [x] running deploy command
npx hardhat run --network polygon scripts/deploy.js
npx hardhat run --network rinkeby scripts/deploy.js
npx hardhat run --network bscTestnet scripts/deploy.js
==> [x] paying for gas transaction: 0 matic
==> [x] Get S. Contract address


[] Verify on Polygon Scan
=> [x] Get a flattened contract
==> [x] create a folder called flattenedContracts
==> [x] execute:
 npx hardhat flatten > ./flattenedContracts/flattenedSmContract.sol  
==> [x] guarantee this comment "// SPDX-License-Identifier: MIT" just appears one time in the entire code.
==> [x] Go to polygon scan and find your smart contract
=> [x] Verify and Publish
==> [x] fill the form
==> [x] pay fees: 0,0047 matic
