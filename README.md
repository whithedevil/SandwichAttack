# SandwichAttack
1.	Go To the Following Repo & Fork the Repo :


  https://www.buildbear.io/resources/guides-and-tutorials/Sandwich_Attack


2.	Once the Cloning is done, Click on Code and copy the HTTPS Link 


3.	Move to the VSC code and Open the Terminal 
git clone Paste The Link


4.	Move to the Tutorial Folder 
cd FolderName



5.	Move to MultiContractTutorial Folder by Following the command 
cd .\MultiContractTutorial\


6.	Run the Following Command to install Packages 
npm install


7.	To Create Testnets 
npm run createTestnets


8.	To deploy all the contracts 
npx hardhat run scripts/deployAll.js


9.	To Run the test scripts 
npm run test


Prerequisites: Node (v18 LTS) plus Yarn (v1.x) and Git
🚨 If you are using a version < v18 you will need to remove openssl-legacy-provider from the start script in package.json
1️⃣ clone/fork 🏗 scaffold-eth x buildbear:
git clone https://github.com/BuildBearLabs/scaffold-eth.git
2️⃣ install and create your private testnet (forked from the mainnet):
cd scaffold-eth
yarn install
yarn fork-bb
3️⃣ 🛰 deploy your SwapOnUniswap Contract:
cd scaffold-eth
yarn deploy
4️⃣ start your 📱 frontend:
🚨 if you have not created your private testnet please follow the the steps in point 2 above:
cd scaffold-eth
yarn start
5️⃣ you can use your 🚰 faucet directly from the terminal after creating your private tesnet:
# for native tokens
yarn faucet-bb native <Insert Amount (optional)> <Insert Your Wallet Address>

# for erc20 tokens
yarn faucet-bb USDC <Insert Amount (optional)> <Insert Your Wallet Address>

# Please note the supported ERC20 tokens below

# by default faucet mints 100 native / erc20 tokens
Supported ERC20 tokens that can be used :
1.	USDC
2.	USDT
3.	DAI
4.	BNB
5.	BUSD
6.	MATIC
7.	WBTC
8.	UNI
9.	AAVE
# Please note the address for each ERC20 Tokens is automatically updated / changed based on the network that you have forked from
🔏 Edit your smart contracts in packages/hardhat/contracts
📝 Edit your frontend App.jsx in packages/react-app/src
💼 Edit your deployment scripts in packages/hardhat/deploy
📱 Open http://localhost:3000 to see the app
📚 Documentation
Documentation, tutorials, challenges, and many more resources, visit: docs.scaffoldeth.io
🔭 Learning Solidity
📕 Read the docs: https://docs.soliditylang.org
📚 Go through each topic from solidity by example editing YourContract.sol in 🏗 scaffold-eth
•	Primitive Data Types
•	Mappings
•	Structs
•	Modifiers
•	Events
•	Inheritance
•	Payable
•	Fallback
📧 Learn the Solidity globals and units

