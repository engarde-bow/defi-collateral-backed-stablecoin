Decentralized Stable Coin Project
Overview
This project is a decentralized stable coin system designed to be minimalistic and maintain a 1 token == $1 peg. It’s similar to DAI, but without governance, fees, and is only backed by WETH and WBTC.

Features
Exogenous Collateral: The system uses external assets (WETH and WBTC) as collateral to issue stable coins.
Dollar Pegged: Each stable coin is pegged to the value of 1 USD, providing stability against market volatility.
Algorithmically Stable: The system uses algorithms to automatically adjust supply and demand, maintaining the stable coin’s peg to the dollar.
How It Works
The system allows users to deposit WETH or WBTC as collateral to mint stable coins. These stable coins are algorithmically pegged to the value of 1 USD. The system uses smart contracts to automatically adjust the supply of stable coins in response to changes in demand, ensuring that the value of each stable coin remains stable at 1 USD.

Getting Started
To get started with this project, clone the repository and install the necessary dependencies.

git clone <repository-url>
cd <repository-directory>
npm install

Testing
This project includes test using fuzz or invariant test.
To run the tests, use the following command:

npm run test

Deployment
To deploy the contracts to a local development network, use the following command:

npm run deploy:local

To deploy the contracts to the mainnet or a testnet, first set up your environment variables, then use the appropriate command:

export INFURA_PROJECT_ID=<your-infura-project-id>
export PRIVATE_KEY=<your-private-key>
npm run deploy:mainnet

Contributing
Contributions are welcome! Please read the contributing guide to get started.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Disclaimer
This is a decentralized application. Use at your own risk. The authors are not responsible for any loss or damage that may occur from the use of this software. Always do your own research and consider the risks before using a decentralized application.