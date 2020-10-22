# Solidity_Simulation_2

These are two solidity contracts that are designed to show an example of a crowdsale for a new coin that is being minted.

The solidity file WindshearCoin is an example of creating a coin and follows the ERC20, ERC20Detailed, and ERC20 Mintable contracts.

The other Solidity file, Crowdsale, contains two contracts, WindshearCoinSale and WindshearCoinSaleDeployer. In order for the crowd sale to work you must first compile the Crowdsale solidity file. After it has been compiled you need to deploy the WindshearCoinSaleDeployer contract first. This will give you two addresses, a token address and a token sale address. 

Next you need to deploy the WindshearCoin contract and set the at address field to the token_address. The last contract,WindshearCoinSale, should now be deployed, settign the at address field to the token sale address. Once this has been done you can now test the contracts on a local network. Once you fill like the conracts are working the way that you want them to you can deploy them to a test network, such as Kovan, so others can interact with them.

That is how you compile and deploy smart contracts for a crowdsale.
