
# 🚀 Bot Setup Instructions

Welcome to the bot setup guide! Follow the steps below to install and configure the bot correctly. This guide is designed to be beginner-friendly, with clear explanations for each step.

> [Termux guides if you run on mobile](https://github.com/MeoMunDep/Guides-for-using-my-script-on-termux)

---

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Installation Steps](#installation-steps)
3. [Configuration Files](#configuration-files)
   - [`configs.json`](#configsjson)
   - [`privateKeys.txt`](#privatekeystxt)
   - [`wallets.txt`](#walletstxt)
   - [`proxies.txt`](#proxiestxt)
4. [Running the Bot](#running-the-bot)
5. [Contact and Support](#contact-and-support)

---

<details>
<summary>Prerequisites</summary>

## Prerequisites

Before running the bot, make sure you have the following installed:

- **Node.js** (Version: `22.11.0`)
- **npm** (Version: `10.9.0`)

Download Node.js and npm here: [Download Link](https://t.me/KeoAirDropFreeNe/257/1462).

-> Double click on `run.bat` for windows or `run.sh` for linux/mac if you want to run automatically, remember to fill all the necessary data.

</details>

<details>
<summary>Installation Steps</summary>

## Installation Steps

1. **Download and Extract the Bot Files:**  
   - Extract the bot package into a folder on your computer.

2. **Install Dependencies:**  
   Open your terminal or command prompt, navigate to the folder where the bot files are located, and run:

```bash
npm install --force user-agents axios meo-forkcy-colors meo-forkcy-utils meo-forkcy-proxy meo-forkcy-logger ethers
````

If you encounter an Execution Policy error on Windows, run:

```bash
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass
```

Then, run the npm install command again.

3. **Prepare Configuration Files:**

   * Ensure all configuration files are set up correctly before running the bot (see Configuration Files section).

</details>

<details>
<summary>Configuration Files</summary>

## Configuration Files

### `configs.json` - 📜 Adjust Bot Settings

This file controls the bot’s behavior. Example:

```json
{
  "rotateProxy": false,
  "skipInvalidProxy": true,
  "proxyRotationInterval": 2,
  "delayEachAccount": [1, 1],
  "timeToRestartAllAccounts": 86400,
  "howManyAccountsRunInOneTime": 1,
  "faucet": true,
  "mint": true,
  "staking": {
    "enable": true,
    "amount": {
      "AUSD": [10, 50],
      "USDe": [10, 50],
      "LVLUSD": [10, 50],
      "vUSD": [5, 10],
      "VANAUSD": [10, 50],
      "azUSD": [1, 5],
      "stATH": [1, 5],
      "0USD": [10, 50],
      "USD1": [10, 20]
    }
  }
}
```

### `privateKeys.txt` - 💼 Wallet Addresses

* Wallets generator: [Link](https://github.com/MeoMunDep/Automatic-Ultimate-Create-Wallets-for-Airdrop)
* EVM privatekey.

```txt
0x...
0x...
0x...
```

### `proxies.txt` - 🌐 Proxy List (Optional)

Supported formats:

```txt
http://host:port
https://host:port
socks4://host:port
socks5://host:port
http://user:pass@host:port
https://user:pass@host:port
socks4://user:pass@host:port
socks5://user:pass@host:port
```

</details>

<details>
<summary>Running the Bot</summary>

## Running the Bot

1. Navigate to the folder containing the bot files:

```bash
cd /path/to/maitrix
```

2. Run the bot using the following command:

```bash
node meomundep.js
```

</details>

<details>
<summary>Contact and Support</summary>

## Contact and Support

* **Help me with your referral** [MAITRIX Link](https://app.testnet.themaitrix.ai/#/home) | [GALXE Tasks](https://app.galxe.com/quest/FUPyKccXmgcMMPVUQi2aF4)

* **ARB SEPOLIA faucet**: [1](https://faucet.quicknode.com/arbitrum/sepolia) - [2](https://www.alchemy.com/faucets/arbitrum-sepolia) - [3](https://bridge.arbitrum.io/)

* **Buy me a telegram account** [Here](https://t.me/KeoAirDropFreeNe/312/27801) or [Here](https://github.com/MeoMunDep/MeoMunDep)

* **Contact:** [Contact Me](https://t.me/MeoMunDep)

* **Group:** [Join the Group](https://t.me/KeoAirDropFreeNe)

* **Channel:** [Visit the Channel](https://t.me/KeoAirDropFreeNee)

Enjoy using the bot! 🚀

</details>


