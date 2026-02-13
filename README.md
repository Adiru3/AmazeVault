# 🛡️ AmazeVault - Multi-Currency Crypto Wallet Bot

**AmazeVault** is a professional, high-performance Telegram cryptocurrency wallet designed for seamless asset management, instant internal trading, and secure blockchain withdrawals. It is a complete solution for anyone looking to run their own crypto-banking service with a built-in revenue model.

---

## 🚀 Core Features

### 💰 Multi-Currency Support
Full support for over **40+ major cryptocurrencies**, including:
- **Major Coins**: BTC, ETH, TON, SOL, TRX, DOGE, LTC.
- **EVM Networks**: BNB Chain, Polygon (POL), Arbitrum, Optimism, Base, Avalanche, and more.
- **Stablecoins**: USDT (ERC20/TRC20), USDC, DAI.

### 🔄 Instant Internal Exchange (Internal Trading)
Users can swap between any supported coins instantly.
- **Zero Gas**: Trading happens within the system's database, meaning no network fees for the user during exchange.
- **Real-Time Rates**: Integrated with **CoinGecko API** for accurate, up-to-the-minute market pricing.

### 📤 Smart Withdrawal System
Complete blockchain withdrawal capabilities with an automated gas management system.
- **Auto-Gas**: The bot automatically estimates network fees and deducts them from the user's internal balance.
- **Zero-Friction**: Users don't need to hold "native" gas coins (like TRX or ETH) to withdraw tokens; the bot handles the conversion and pre-payment.

### 🌐 Global Localization
Fully translated into **5 languages** to reach a worldwide audience:
- 🇬🇧 English
- 🇷🇺 Russian
- 🇺🇦 Ukrainian
- 🇹🇷 Turkish
- 🇸🇦 Arabic

---

## 🛠️ Technical Excellence

### 📦 Zero-Dependency Portable Runtime
The project comes with a **Portable Python Runtime**, allowing it to run on any Windows VPS/PC without installing Python or libraries globally.
- **`start.bat`**: Single-click activation for the Bot and Backup Service.
- **Standalone**: All dependencies are self-contained in the `runtime` folder.

### 🛡️ Automated Security
- **Real-Time Backups**: A dedicated watcher script (`db_backup.py`) monitors the database and sends a backup file directly to the owner's Telegram DM whenever a change occurs.
- **State-of-the-Art Cryptography**: Deterministic wallet generation using Bip39 mnemonics ensures user keys are manageable and safe.

---

*Developed with focus on speed, anonymity, and profitability.*



