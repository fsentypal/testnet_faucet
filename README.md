Demo Video: https://www.youtube.com/watch?v=Lh81kPCH6nk&ab_channel=FilipSentypal


Disclaimer: This project may rely on minimal code but is mostly run and is functional in the hardhat environment that you set up using your MetaMask account and testnet of choice.

Overview:
This project is set up for Ethereum blockchain development using Hardhat, a popular development environment for compiling, deploying, testing, and debugging Ethereum software. The configuration files included in this project are tailored for different purposes and environments.

Files and Their Purposes:
georli_config.txt:

This file is configured for connecting to the Goerli test network via Alchemy. It enables forking, allowing you to work with a local version of the Goerli network. This is useful for testing without spending real Ether.
hardhat.config.js:

The main configuration file for Hardhat. It's set up with the Solidity version 0.8.19. The networks section is currently configured only for the default Hardhat network, which is a local development network.
package-lock.json:

It lists the exact dependency tree installed in your project. This ensures that the same versions of the dependencies are installed in different environments.
package.json:

Defines the project's dependencies and other metadata. This project depends on Hardhat and several related plugins like @nomicfoundation/hardhat-network-helpers and @nomicfoundation/hardhat-toolbox.
.gitignore:

Specifies intentionally untracked files to ignore, like node_modules, .env, and various Hardhat-generated files (cache, artifacts, etc.).
Prerequisites:
Node.js and npm (Node Package Manager).
A basic understanding of Ethereum and Solidity.
Familiarity with Hardhat for Ethereum development.
Installation:
To set up the project:

Clone the repository.
Run npm install to install the dependencies.
Usage:
Use npx hardhat to run Hardhat tasks.
Modify georli_config.txt to connect to different Ethereum networks or customize the Hardhat environment.
package.json and package-lock.json should be updated as dependencies change or are added.
Versioning:
Ensure to keep the Solidity version and Hardhat dependencies updated as per your project requirements.

Try running some of the following tasks:

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
npx hardhat run scripts/deploy.js
```
