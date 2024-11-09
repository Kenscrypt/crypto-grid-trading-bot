# Solana Grid Trading Bot

A grid trading bot specifically designed for Solana (SOL) cryptocurrency trading. This bot utilizes grid trading strategies to automate buying and selling SOL on the Solana blockchain, taking advantage of low transaction fees to optimize profit. With adjustable parameters, users can customize the bot's behavior based on market conditions and their trading goals.

## How Grid Trading Bots Work

Grid trading is a strategy that profits from market fluctuations. The bot automatically buys and sells small amounts of SOL at predetermined intervals (grids) based on user-defined parameters. When the price of SOL dips, the bot opens a "position" by purchasing SOL, and when the price increases, it sells that position, locking in profit. Each price movement within the grid opens a new position or closes an existing one, aiming to maximize gains from market volatility.

## Important Notice

Please ensure that your wallet contains USDC tokens on the Solana blockchain. The bot will automatically handle buying and selling of USDC for SOL and vice versa based on your trading settings. 

Do not delete or manually modify any of the text files (`pozicije.txt`, `log.txt`, `istorija.txt`, `rpcFile.json`), as the bot relies on these files for proper operation. Any deletion or alteration of their values may cause the bot to malfunction. If you need to reset or update any file data, please contact our support team at [kenscrypt@gmail.com](mailto:kenscrypt@gmail.com) for assistance.

## Requirements

- **OS**: Windows, Linux or MacOSX
- **Solana Wallet**: A wallet with the private key in WIF format
- **RPC URL Providers**: Accounts on Alchemy, Shyft.to, QuickNode, and InstaNode for obtaining RPC links to Solana’s mainnet.

## Important System Requirement

Please ensure that the terminal running the bot remains active 24/7, as well as the computer on which the bot is running, to ensure continuous trading without interruptions.

## Fees

The bot charges a fee of 10% on the profits it generates. This fee is automatically deducted each time the bot makes a profit. This means you only pay fees based on the successful trades the bot executes, ensuring that your initial capital remains intact while you benefit from the bot's trading strategies.

## Quick Start Guide

1. **Download Bot Files**: Download the appropriate `.7z` file for your platform (Windows or Linux) and extract its contents into a single folder. Ensure that the files inside the extracted folder are not modified. The following files will be included:
    - `trading_bot.exe` (for Windows) or `trading_bot` (for Linux)
    - `pozicije.txt`
    - `log.txt`
    - `istorija.txt`
    - `rpcFile.json`

2. **Set Up Terminal**:
   - **Windows**:
     - Open Command Prompt (`cmd`).
     - Use the `cd` command to navigate to the folder where you saved the bot files.
   - **Linux**:
     - Open the terminal.
     - Use `cd` to go to the folder where you saved the bot files.
   - **MacOSX**:
     - Open the terminal.
     - Use `cd` to go to the folder where you saved the bot files.

3. **Run the Bot**:
   - **Windows**: Type `trading_bot.exe` and press Enter.
   - **Linux**: Type `./trading_bot` and press Enter.
   - **MacOSX**: Type `./trading_bot` and press Enter.

4. **Enter Your Private Key**:
   - The bot will prompt you to enter your private key in WIF format. This key is found in your Solana wallet (look for a long string starting with a number or letter, e.g., `4fedLaBMdXDHfsEbDST7LAzWp78N6KahLATaY22gzdSoP852U1EX7MTSVsjmLtYiRGmCWULnyaWh1o8oaAPAf8eY`).

5. ## Obtain RPC Links

    We recommend using the following platforms to obtain RPC links for Solana's mainnet and entering them in our program in the following order:
    
    - [InstaNode](https://www.instanode.com/)
    - [Shyft.to](https://shyft.to/)
    - [Alchemy](https://www.alchemy.com/)
    - [Tatum](https://tatum.io/chains/solana?gclid=Cj0KCQjwvpy5BhDTARIsAHSilyl86c-Gn1YK8AkBgQmBU01-DSw7vCOpHEE-52bX2Eb2naPVnAWEWzAaAuTSEALw_wcB&utm_content=695513777478&utm_term=solana%20rpc%20nodes&utm_source=google&utm_medium=cpc&utm_campaign=21154471190&hsa_acc=2664813199&hsa_cam=21154471190&hsa_grp=166249297571&hsa_ad=695513777478&hsa_src=g&hsa_tgt=kwd-1641675695499&hsa_kw=solana%20rpc%20nodes&hsa_mt=p&hsa_net=adwords&hsa_ver=3&gad_source=1)
    
    To get started, sign up on any of these platforms to generate an RPC link for Solana's mainnet. Please ensure to choose the FREE tier option, as this is sufficient for the bot's operation. This step is only necessary during the initial setup of the bot. Alternatively, you can use any other Solana RPC node provider of your choice.


7. **Specify Trading Amount**:
   - Input the amount of money you want to allocate for trading, such as `200` for 200 USD.

8. **Define a Position**:
   - A "position" is opened when the bot buys SOL at a specific price and closed when it sells SOL at a higher price. The difference in price is your profit.

9. **Set the Grid Step**:
   - Enter a `grid step`, which is the price interval at which the bot will open new positions. For example, if SOL is initially bought at $150 and your grid step is 2, the bot will open another buy position if SOL's price drops below $148.
   - **Recommended**: Ensure that `numberOfPositions * gridStep > 30` for optimal performance.


## Support

If you have any questions about setting up the bot, issues with its performance, or suggestions for improvement, please feel free to reach out to our developers. We’re here to help and always open to feedback!

**Contact us at**: [kenscrypt@gmail.com](mailto:kenscrypt@gmail.com)
