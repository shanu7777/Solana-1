# Transfer-SOL-to-New-Wallet

This project is a simple web application that facilitates interaction with a Solana wallet (e.g., Phantom Wallet) to send SOL tokens to a specified account address. The Solana Web3.js library is utilized for blockchain interactions.

![Solana Logo](https://cryptologos.cc/logos/solana-sol-logo.png?v=024)

## Project Overview

- Connect Wallet:Click the "Connect" button to establish a connection with your Solana wallet. The default wallet used in this project is [Phantom Wallet](https://phantom.app/).

- **Send SOL:** Enter the desired amount of SOL in the input field and click the "Send" button to initiate the transaction.

## Getting Started

1. Clone this repository to your local machine.


2. Open the `index.html` file in a web browser.

## Usage

### Connect Wallet

1. Click the "Connect" button to link your Solana wallet (e.g., Phantom Wallet).

2. If you're using Phantom Wallet, it will prompt you to authorize the connection. Follow the on-screen instructions.

3. Once connected, the "Connect" button will change to "Connected."

### Send SOL

1. Enter the amount of SOL you want to send in the input field labeled "Sol to send."

2. Click the "Send" button to initiate the transaction.

3. A status message will indicate the transaction's progress.

4. The transaction will be confirmed on the Solana blockchain.

### Address Ellipsis

The project includes a function that shortens long Solana addresses for display. Addresses longer than 35 characters are displayed as a shortened version with an ellipsis in the middle.

### Troubleshooting

- Check the browser's console for error messages if you encounter any issues with the connection or transaction.

## Dependencies

- [Solana Web3.js](https://github.com/solana-labs/solana-web3.js): Used for interacting with the Solana blockchain.

## Notes

- This is a simplified example for educational purposes and may not cover all security and error-handling considerations for a production application.

- Ensure you have a Solana wallet extension (e.g., Phantom Wallet) installed in your browser.

- Use a Solana development network (e.g., Devnet) for testing. Sending real SOL tokens on the mainnet can result in financial loss.

## Commands

Ensure Solana is installed before running these commands.

1. Generate a new Solana key pair and save it to a JSON file.
   ```bash
   solana-keygen new -o /path/to/new-keypair.json
   ```

2. Set the Solana cluster URL to the Devnet cluster.
   ```bash
   solana config set --url https://api.devnet.solana.com
   ```

3. Request an airdrop of 1 SOL to a specified public key on the Solana blockchain.
   ```bash
   solana airdrop 1 <Public Key>
   ```

4. Check the SOL token balance associated with the currently configured wallet.
   ```bash
   solana balance
   ```

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to customize this README.md file with additional information or instructions specific to your project.
