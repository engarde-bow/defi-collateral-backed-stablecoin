Decentralized Stable Coin Project
Overview
This project is a decentralized stable coin system designed to be minimalistic and maintain a 1 token == $1 peg. It’s similar to DAI, but without governance, fees, and is only backed by WETH and WBTC.

Features
Exogenous Collateral: The system uses external assets (WETH and WBTC) as collateral to issue stable coins.
Dollar Pegged: Each stable coin is pegged to the value of 1 USD, providing stability against market volatility.
Algorithmically Stable: The system uses algorithms to automatically adjust supply and demand, maintaining the stable coin’s peg to the dollar.
How It Works
The system allows users to deposit WETH or WBTC as collateral to mint stable coins. You must always have more collateral deposited than Stable Coins minted. There are constant checks to make sure this health factor is not broken. If the health factor is broken, for example in the event of a sudden and sharp drop in WETH or WBTC, the user may be liquidated. Users are rewarded for liquidating postions that are under-collateralized, in order to keep total collateral above the total supply of minted stable coins, and thus keep the peg...well...stable.


Testing
This project includes tests using fuzz or invariant tests.


Contributing
Contributions are welcome! Please read the contributing guide to get started.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Disclaimer
This is a decentralized application. Use at your own risk. The authors are not responsible for any loss or damage that may occur from the use of this software. Always do your own research and consider the risks before using a decentralized application.
