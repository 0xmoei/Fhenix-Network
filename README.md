# Deploy Contract on Fhenix Testnet

## Wallet
1. Create a Metamask wallet ( Use the wallet you connected to Discord Quests)
2. Get Faucet by typing /faucet in [Discord](https://discord.gg/fhenix-io) OR [Bridge](https://bridge.helium.fhenix.zone/) from Sepolia

## Add Fhenix Testnet to Metamask
1- Open MetaMask in your browser and click on the Ethereum network.

2- Click Add Network.

3- Click Add a network manually.

4- Fill out the network details form. To add a custom network, fill in the following fields:

* Network Name: Fhenix Helium
* New RPC URL: https://api.helium.fhenix.zone
* Chain ID: 8008135
* Currency Symbol: tFHE
* Block Explorer URL: https://explorer.helium.fhenix.zone

## Deploy Contract using Remix (Manually)
**1- Visit [Remix](https://remix.ethereum.org/)**

**2- Create a `SimpleStorage.sol` file and paste [This](https://raw.githubusercontent.com/0xmoei/Fhenix-Network/refs/heads/main/SimpleStorage.sol) in editing menu**

![image](https://github.com/user-attachments/assets/e6c8742f-83c0-4682-b548-54dc4a27b9dc)

**3- Compile your contract file using compiler version 8.26**

![image](https://github.com/user-attachments/assets/3e704184-0a70-4afa-89c2-f800bbc350fc)

**4- Deploy your Contract**
* Change `Environment` to Metamask
* Make sure your wallet is on Fhenix Testnet Network
* Click on Deploy
* After you sign wallet tx, You'll see your deployed contract address appears

![Screenshot_305](https://github.com/user-attachments/assets/e011d2be-8b01-48fc-9996-d1c188283ff6)

### Check you address here
https://explorer.helium.fhenix.zone/

## Complete Quest: Deployed Contracts
You can Verify your deployed contracts on Discord Quests
* **Remember: You'd better NOT click on `submit` but press `Edit` & `verify` again the quest if you want to deploy more to get more points. Once you click `submit`, the quest gets closed and you are not able to get more points**

## Verify Contract (Manually)
1. Go to the deployed Contract page in [Explorer](https://explorer.helium.fhenix.zone/)
2. If you choose `Contract` **tab**, You see a `green tick` besides it meaning Contract ia verified automatically since it is known by the explorer

![Screenshot_308](https://github.com/user-attachments/assets/f824b88e-1bb9-4986-9d63-61661af5a01e)


#


**If it's NOT verified**, You can Click `Publish & Verify` and Verify it by simply choose `Flattened source code`, Paste your `Contract code `,and Click `Publish & Verify`

![Screenshot_309](https://github.com/user-attachments/assets/4496368c-a81c-41c3-8306-0a017894273a)

#

## Complete Quest: Contract Creation and Verification Discord
Do not `submit` if you want to get more points. Click `Edit` ,then `Verify` again after you deployed and verified more Contracts
![Screenshot_310](https://github.com/user-attachments/assets/2cc68e1e-d2a8-4c9d-97d6-dada35d3e058)


