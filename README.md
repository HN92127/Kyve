Steps to create a Kyve node (using pre-built binaries)
1.  Follow the official guide here:
https://docs.kyve.network/intro/protocol-node.html
2.  Create a Kyve Wallet (i.e. Keplr).  Note down the mnemonic seed phrase.  
3.  Create an Arweave Wallet (Arweave Web Wallet).  Fund Arweave with $AR from your Kucoin account.  Save the wallet json file into a local folder to be ready for step 6.  To claim free tokens, you can use the link: https://faucet.arweave.net/
5.  Using https://app.kyve.network/ access the Validators tab and click on being a Validator.  Go through all of the approval steps and download the pre-built binaries file
for the appropriate OS.
5.  If running on an Ubuntu VPS, we can download the Linux binaries file to a Windows machine.
6.  Upload wallet json file (step 3) and the Linux binaries file (step 5) to Ubuntu VPS folder using WinSCP via ssh.
7.  Logon to your Ubutu Server and change directory to location of the json file and the Linux binaries file above.  
8.  To run the binaries file, use the following command format using the appropriate settings for your wallets/pool:
./evm-macos --poolId 0 --mnemonic "your mnemonic in here ..." --initialStake 10000 --keyfile ./arweave.json --network korellia


