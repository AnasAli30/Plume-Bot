## Installation

- Before using this script, make sure you have ETH faucet on Plume testnet
- Open Github Codespace/Gitpod/Any Other Terminal
- Paste this below command, also before pasting command, you should verify these codes in `Plume.sh` file
```bash
wget https://raw.githubusercontent.com/AnasAli30/Plume-Bot/main/Plume.sh && touch privatekeys.txt && nano privatekeys.txt
```
- You need to import your private Key here (1 Private key in each line)
- Now press `Ctrl+S` then `Ctrl+X` and then press Enter
- You can verify whether you have successfully entered your wallets' private key or not using `cat privatekeys.txt`
- Now use these commands
```bash
chmod +x Plume.sh && ./Plume.sh
```
