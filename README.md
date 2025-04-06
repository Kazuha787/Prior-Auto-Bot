# Prior Auto Bot

![IMG_20250406_102444_070](https://github.com/user-attachments/assets/c6fa7032-04f7-49b2-8542-435cd1729880)

This bot automates swapping PRIOR tokens for USDT/USDC on the **Base Sepolia** testnet to help users participate in the PRIOR airdrop activity—no manual hassle, just set it and forget it.

# ⚡ Prior Auto Bot by [Kazuha](https://github.com/Kazuha787) ⚡
# ⚡ Telegram [CHANNEL](https://t.me/Offical_Im_kazuha)
---

## Features

- Supports multiple wallets via `.env` file
- Automatic approval of PRIOR tokens (because who’s got time to click?)
- Randomized swap amounts (between `0.001` and `0.002` PRIOR)
- Random token swap target (USDT or USDC)
- Detailed logs with status emojis for quick visual feedback
- ETH, PRIOR, USDT, and USDC balance checks before and after

---

## Prerequisites

- Node.js (v14 or higher)
- NPM or Yarn
- Private keys for wallets loaded with Base Sepolia ETH and PRIOR tokens

---

## Setup Instructions

Faucet & Bridging Resources

1. Get ETH on Sepolia (Main)

Use this Google faucet: https://cloud.google.com/application/web3/faucet/ethereum/sepolia

2. Bridge ETH to Base Sepolia

Bridge your Sepolia ETH to Base Sepolia: https://superbridge.app/base-sepolia

3. Register for PRIOR Faucet

Claim PRIOR testnet tokens here: https://testnetpriorprotocol.xyz/faucet

### 1. Clone This Repository

```bash
git clone https://github.com/Kazuha787/Prior-Auto-Bot.git
cd Prior-Auto-Bot
```
2. Install Dependencies
```
npm install
```

3. ## Configure Wallets

Create a .env file in the root directory and add your private keys like this:
```sh
RPC_URL=https://sepolia.base.org
PRIVATE_KEY=Your_key
```

> Reminder: Never expose your private keys publicly. Testnet or not, good habits matter.


## Usage

## To run the bot:
```sh
npm start
```

The bot will:

1. Display all loaded wallets
2. Ask how many swaps you want to perform per wallet
3. Pick random tokens (USDT or USDC) and swap random amounts of PRIOR
4. Show wallet balances before and after all operations
--
Smart Contract Addresses (Base Sepolia)

PRIOR Token: `0xc19Ec2EEBB009b2422514C51F9118026f1cD89ba`

USDT Token: `0x014397DaEa96CaC46DbEdcbce50A42D5e0152B2E`

USDC Token: `0x109694D75363A75317A8136D80f50F871E81044e`

Router: `0x0f1DADEcc263eB79AE3e4db0d57c49a8b6178B0B`

---

## Network Config

Network: Base Sepolia Testnet

Chain ID: 84532

RPC URL: https://base-sepolia-rpc.publicnode.com


## Security Notice

Store your .env file securely

This tool is for testnet use only

Never use mainnet private keys here. Ever.



---

Disclaimer

This project is strictly for educational and testing purposes. Use it at your own risk. We are not responsible for any losses, bugs, or intergalactic wormholes caused by running this bot.

---

## License

MIT License
