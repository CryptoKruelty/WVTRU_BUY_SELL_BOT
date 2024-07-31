WVTRU Bot
================
*A bot for automating WVTRU transactions on the Vitruveo blockchain.*

Getting Started
---------------
### 1. Rename the `.env_example` file to `.env`
You'll find a file named `.env_example` in the same directory as the bot executable. Rename this file to `.env`.

### 2. Add your Vitruveo wallet credentials to the `.env` file
> **IMPORTANT**: Before proceeding, please make sure you understand the importance of keeping your private key safe. **DO NOT** use your main wallet's private key with this bot. Instead, create a new wallet specifically for this purpose and fund it with the amount of VTRU you wish to wrap.

Open the newly renamed `.env` file and add your Vitruveo wallet credentials. You'll need to add the following variables:
* `KEY`: Your Vitruveo wallet private key
* `BUY_AMOUNT`: The amount of WVTRU to buy
* `BUY_TARGET`: The price target for buying WVTRU
* `SELL_TARGET`: The price target for selling WVTRU
* `MAX_BUYS`: The maximum number of buys to perform
* `MULTIPLE_BUYS`: Set to `true` to enable multiple buys

> Here's an example of what the `.env` file should look like:

Environment Variables
* `KEY`: Your Vitruveo private key
* `BUY_AMOUNT`: 100
* `BUY_TARGET`: 1.5
* `SELL_TARGET`: 2.5
* `MAX_BUYS`: 5
* `MULTIPLE_BUYS`: false

### **Next Steps**
### 3. Save the .env file
Once you've added your credentials to the .env file, save it and close the file.
### 4. Run the bot
You can now run the bot by simply clicking on the executable file (WVTRU_Buy_Sell.exe). The bot will start running and will automatically send WVTRU transactions based on the settings in your .env file.

### Notes

**Important**: Make sure to keep your .env file secure and do not share it with anyone.
Make sure to enter the correct private key and value in the .env file to avoid any errors.

>The bot will automatically sell any wrapped VTRU (WVTRU) in your wallet address for USDC.
Important Disclaimer
Please be aware that there is a 3% tax for using this bot. This means that 3% of the VTRU you wrap will be deducted as a fee. By using this bot, you acknowledge that you have read and understood the terms and conditions, including the 3% tax on all transactions.