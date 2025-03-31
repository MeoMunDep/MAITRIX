# 🚀 Bot Setup Instructions


Welcome to the bot setup guide! Follow the steps below to install and configure the bot correctly. This guide is designed to be beginner-friendly, with clear explanations for each step.

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux)

---

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Installation Steps](#installation-steps)
3. [Configuration Files](#configuration-files)
   - [`configs.json`](#1-configsjson)
   - [`privateKeys.txt`](#2-privateKeystxt)
   - [`wallets.txt`](#3-walletstxt)
   - [`proxies.txt`](#4-proxiestxt)
4. [Running the Bot](#running-the-bot)
5. [Contact and Support](#contact-and-support)

---

## Prerequisites

Before running the bot, make sure you have the following installed:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).

-> Double click on `run.bat` for windows or `run.sh` for linux/mac if you want to run automatically, remember to fill all the necessary data.

---

## Installation Steps

1. **Download and Extract the Bot Files:**

   - Extract the bot package into a folder on your computer.

2. **Install Dependencies:**
   Open your terminal or command prompt, navigate to the folder where the bot files are located, and run:

   ```bash
   npm install --force user-agents axios colors p-limit https-proxy-agent socks-proxy-agent ethers web3
   ```

   If you encounter an Execution Policy error on Windows, run:

   ```bash
   Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
   ```

   Then, run the npm install command again.

3. **Prepare Configuration Files:**
   - Ensure all configuration files are set up correctly before running the bot (see [Configuration Files](#configuration-files) section).

---

## Configuration Files

### 1. `configs.json` - 📜 Adjust Bot Settings

This file controls the bot’s behavior. Below is an example configuration:

```json
{
  "timeZone": "en-US",
  "rotateProxy": false,
  "skipInvalidProxy": false,
  "proxyRotationInterval": 2,
  "delayEachAccount": [1, 1],
  "timeToRestartAllAccounts": 300,
  "howManyAccountsRunInOneTime": 46,
  "amountOfAUSDStaking": [0.1, 0.5]
}
```

- **Fields Explained:**
  - `timeZone`: Time zone setting (e.g., "en-US").
  - `rotateProxy`: Enable or disable proxy rotation.
  - `skipInvalidProxy`: Skip invalid proxies if `true`.
  - `proxyRotationInterval`: Time interval (in minutes) for rotating proxies.
  - `delayEachAccount`: Random delay range (in seconds) between accounts.
  - `amountOfAUSDStaking`: Amount of AUSD to stake.
  - `timeToRestartAllAccounts`: Time (in seconds) to restart all accounts.
  - `howManyAccountsRunInOneTime`: Number of accounts to run simultaneously.

### 2. `privateKeys.txt` - 💼 Wallet Addresses

- Wallets generator: [Link](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)
- EVM privatekey.

```txt
0x...
0x...
0x...
```

_Note: Each row for each account_

### 3. `proxies.txt` - 🌐 Proxy List (Optional)

If you are using proxies, add them here. Leave the file blank if you are not using proxies. Supported formats:

```txt
http://user:password@host:port
https://user:password@host:port
socks4://user:password@host:port
socks5://user:password@host:port
```

_Note: each row for each account_

---

## Running the Bot

1. Navigate to the folder containing the bot files:

   ```bash
   cd /path/to/meomundep-folder
   ```

2. Run the bot using the following command:
   ```bash
   node meomundep.js
   ```

---

## Contact and Support

- **Help me with your referral** [MAITRIX Link](https://app.testnet.themaitrix.ai/#/home) | [GALXE Tasks](https://app.galxe.com/quest/FUPyKccXmgcMMPVUQi2aF4)
- **ARB SEPOLIA faucet**: [1](https://faucet.quicknode.com/arbitrum/sepolia) - [2](https://www.alchemy.com/faucets/arbitrum-sepolia) - [3](https://bridge.arbitrum.io/) | Access these link to bridge SEPOLIA to ARBITRUM SEPOLIA - [1](https://rinkeby.orbiter.finance/en?dest=G%C3%B6rli&src_chain=11155111&tgt_chain=421614&src_token=ETH) - [2](https://testnets.relay.link/bridge/arbitrum-sepolia?fromChainId=11155111&fromCurrency=0xfff9976782d46cc05630d1f6ebab18b2324d6b14&toCurrency=0x0000000000000000000000000000000000000000)
- **Buy me a telegram account** [Here](https://t.me/KeoAirDropFreeNe/312/27801) or [Here](https://github.com/MeoMunDep/MeoMunDep)

If you encounter any issues or have questions, feel free to reach out:

- **Contact:** [Contact Me](https://t.me/MeoMunDep)
- **Group:** [Join the Group](https://t.me/KeoAirDropFreeNe)
- **Channel:** [Visit the Channel](https://t.me/KeoAirDropFreeNee)

Your support is greatly appreciated! 🐱

---

Enjoy using the bot! 🚀
