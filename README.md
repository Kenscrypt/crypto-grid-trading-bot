# Solana Grid Trading Bot

A grid trading bot specifically designed for Solana (SOL) cryptocurrency trading. This bot utilizes grid trading strategies to automate buying and selling SOL on the Solana blockchain, taking advantage of low transaction fees to optimize profit. With adjustable parameters, users can customize the bot's behavior based on market conditions and their trading goals.

## How Grid Trading Bots Work

Grid trading is a strategy that profits from market fluctuations. The bot automatically buys and sells small amounts of SOL at predetermined intervals (grids) based on user-defined parameters. When the price of SOL dips, the bot opens a "position" by purchasing SOL, and when the price increases, it sells that position, locking in profit. Each price movement within the grid opens a new position or closes an existing one, aiming to maximize gains from market volatility.

## Important Notice

Please ensure that your wallet contains USDC tokens on the Solana blockchain. The bot will automatically handle buying and selling of USDC for SOL and vice versa based on your trading settings. 

Do not delete or manually modify any of the text files (`pozicije.txt`, `log.txt`, `istorija.txt`), as the bot relies on these files for proper operation. Any deletion or alteration of their values may cause the bot to malfunction.

If you need to reset or update any file data, please contact our support team at [kenscrypt@gmail.com](mailto:kenscrypt@gmail.com) for assistance.

## Requirements

- **OS**: Windows or Linux
- **Solana Wallet**: A wallet with the private key in WIF format
- **RPC URL Providers**: Accounts on Alchemy, Shyft.to, QuickNode, and InstaNode for obtaining RPC links to Solana’s mainnet.

## Quick Start Guide

1. **Download Bot Files**: Download the `trading_bot.exe` executable (for Windows) or the Linux version (`trading_bot`) and the following text files to a single folder:
    - `pozicije.txt`
    - `log.txt`
    - `istorija.txt`
    - `rpcFile.json`

2. **Set Up Terminal**:
   - **Windows**:
     - Open Command Prompt (`cmd`).
     - Use the `cd` command to navigate to the folder where you saved `trading_bot.exe`.
   - **Linux**:
     - Open the terminal.
     - Use `cd` to go to the folder where you saved `trading_bot`.

3. **Run the Bot**:
   - **Windows**: Type `trading_bot.exe` and press Enter.
   - **Linux**: Type `./trading_bot` and press Enter.

4. **Enter Your Private Key**:
   - The bot will prompt you to enter your private key in WIF format. This key is found in your Solana wallet (look for a long string starting with a number or letter, e.g., `5KQwrPbwpL6PjXujaW31FSSQz2rP8za4BL1b4TGKnCmQ`).

5. **Obtain RPC Links**:
   - Sign up on Alchemy, Shyft.to, QuickNode, and InstaNode.
   - Generate an RPC link for Solana’s mainnet (this step is only required for the first time).

6. **Specify Trading Amount**:
   - Input the amount of money you want to allocate for trading, such as `200` for 200 USD.

7. **Define a Position**:
   - A "position" is opened when the bot buys SOL at a specific price and closed when it sells SOL at a higher price. The difference in price is your profit.

8. **Set the Grid Step**:
   - Enter a `grid step`, which is the price interval at which the bot will open new positions. For example, if SOL is initially bought at $150 and your grid step is 2, the bot will open another buy position if SOL's price drops below $148.
   - **Recommended**: Ensure that `numberOfPositions * gridStep > 30` for optimal performance.


## Support

If you have any questions about setting up the bot, issues with its performance, or suggestions for improvement, please feel free to reach out to our developers. We’re here to help and always open to feedback!

**Contact us at**: [kenscrypt@gmail.com](mailto:kenscrypt@gmail.com)

