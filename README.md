# ⚡ ArcPay — USDC Payments on Arc Testnet

A clean, minimal USDC payment app built on [Arc](https://arc.io) — Circle's institutional blockchain. Send USDC with sub-second finality, no ETH gas required.

![Arc Testnet](https://img.shields.io/badge/Network-Arc%20Testnet-00d4ff?style=flat-square)
![USDC](https://img.shields.io/badge/Token-USDC-2775ca?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

---

## ✨ Features

- ⚡ Send USDC on Arc Testnet in one click
- 🦊 OKX Wallet & MetaMask support (any EVM wallet)
- 🔄 Auto network detection + one-click switch to Arc Testnet
- 💼 Live USDC balance display
- 🧾 Optional memo/note for each payment
- 🔍 ArcScan transaction link after every send
- 📱 Fully responsive — works on mobile
- 🗂️ Zero dependencies — pure HTML/CSS/JS (ethers.js via CDN)

---

## 🚀 Quick Start

### Option 1 — Open directly in browser
Just open `index.html` in any browser. No server needed.

### Option 2 — Serve locally
```bash
npx serve .
# or
python3 -m http.server 3000
```

### Option 3 — Deploy free (GitHub Pages / Netlify)
Push to GitHub → Enable GitHub Pages on the repo → Done.

---

## 🦊 Wallet Setup — Arc Testnet

Add Arc Testnet to your OKX Wallet or MetaMask manually:

| Setting | Value |
|---|---|
| Network Name | `Arc Testnet` |
| RPC URL | `https://rpc.testnet.arc.io` |
| Chain ID | `1261` |
| Currency Symbol | `USDC` |
| Block Explorer | `https://testnet.arcscan.app` |

Get free testnet USDC: [faucet.arc.io](https://faucet.arc.io)

---

## 🗂️ Project Structure

```
arcpay/
├── index.html      # Full app — single file, no build step
└── README.md
```

---

## 🔧 Configuration

In `index.html`, update these constants if Circle publishes a new USDC contract address:

```js
const ARC_CHAIN_ID = '0x4ED';           // 1261 decimal
const USDC_ADDRESS = '0x1c7D4B...';     // Update at mainnet launch
```

---

## 🛣️ Roadmap

- [ ] Payment request / invoice link generator
- [ ] QR code for receiving USDC
- [ ] Transaction history log (local storage)
- [ ] Multi-token support
- [ ] Mainnet launch support

---

## 🌐 Built With

- [Arc](https://arc.io) — Circle's institutional blockchain
- [Circle USDC](https://circle.com) — World's leading regulated stablecoin
- [ethers.js v6](https://ethers.org) — Ethereum library
- Pure HTML/CSS/JS — no framework, no build tool

---

## 📄 License

MIT — free to use, fork, and build on.

---

> Built as an open contribution to the Arc ecosystem. Mainnet launching Summer 2026.
