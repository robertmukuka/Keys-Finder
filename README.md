## Keys-Finder

Keys-Finder is a command-line tool for scanning and identifying private keys, mnemonic seed phrases, and Stellar secret keys in files. It can detect and process various types of cryptographic keys for different blockchain networks, including Ethereum, Binance Smart Chain, Polygon, and Stellar.

## Installation
To use Keys-Finder, follow the steps below:

Ensure you have Node.js installed on your system.

Clone the repository or download the source code files.

Open a terminal or command prompt and navigate to the project directory.

Run the following command to install the required dependencies:

npm install

###Usage

Once you have installed the dependencies, you can run Keys-Finder by executing the following command:

node keys-finder.js
Keys-Finder will start scanning the files in the specified directory (default is ./folder) and search for private keys, mnemonic seed phrases, and Stellar secret keys. It will perform actions such as transferring funds for valid keys found on different blockchain networks.

## Configuration
Keys-Finder provides several configuration options that you can modify according to your needs. Open the keys-finder.js file and adjust the following variables:

ethereumRecipientAddress: Ethereum address to transfer funds.
bscRecipientAddress: Binance Smart Chain address to transfer funds.
polygonRecipientAddress: Polygon address to transfer funds.
stellarRecipientAddress: Stellar address to transfer funds.
ethereumRpcUrl: Ethereum JSON-RPC URL.
bscRpcUrl: Binance Smart Chain JSON-RPC URL.
polygonRpcUrl: Polygon JSON-RPC URL.
folderPath: Path to the directory containing the files to be scanned.
Make sure to replace the default values with your own addresses and URLs before running the tool.

### License
Free to Use...(Educational purposes only)

## Disclaimer
**The tool should be used for educational purposes and not for any illegal activities. Use this tool responsibly and at your own risk. Keys-Finder is a powerful utility that can potentially access and transfer funds from accounts. Ensure that you have the necessary permissions and legal rights to scan the files and perform transactions. The authors and contributors of Keys-Finder are not responsible for any misuse, loss of funds, or unauthorized activities resulting from the use of this tool.**

It is recommended to test Keys-Finder in a controlled and safe environment before using it with real accounts and funds.

## Contributions
Contributions to Keys-Finder are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request on the project's GitHub repository.

## Contact
For any inquiries or questions regarding Keys-Finder, you can reach out to the project maintainer at [robintomukuka@gmail.com]

If you like this tool, please feel free to make contributions!

Stellar: GB46JMLXQ6JN5637WOLLY5KWWJ2YRPUULVW6GY45YDNLFLAQ5QI4UCFC
Eth/BNB/Polygon: 0x23E41e63Eb5d29aC76713a506F374AeF1Feb6eBD
TRON: TKKuG3sHjnXbP8L38dRpTvSDTvTaqfFqxy
BTC: bc1qs0udrsrgn2q3cj4edqdkndg2gq4t3l2p43f8tg
LTC: Le5Xs43GpVAvLQ5TxBM7zHFsxwufRHWUJv
