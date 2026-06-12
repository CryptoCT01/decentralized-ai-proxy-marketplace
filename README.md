# Decentralized AI Proxy Marketplace

A privacy-first, trust-minimized marketplace for AI inference.

> **Safety Note**: These HTML dashboards are fully client-side interactive demos. No real API keys, private keys, or sensitive data are exposed. All transactions, earnings, and responses are simulated for demonstration purposes only. You can safely open and interact with them in any browser.

**Live Demos** (open directly in browser):
- [Seller Dashboard](https://github.com/CryptoCT01/decentralized-ai-proxy-marketplace/blob/main/seller-dashboard.html)
- [Buyer Dashboard](https://github.com/CryptoCT01/decentralized-ai-proxy-marketplace/blob/main/buyer-dashboard.html)

## Features
- TEE-protected prompt privacy (sellers cannot see prompts)
- On-chain escrow and pay-per-token settlement
- Collateral staking with slashing for reliability
- Real-time interactive dashboards (Seller & Buyer)
- MetaMask wallet integration
- Works with both API keys and self-hosted GPU compute

## Tech Stack
- Solidity smart contracts (escrow + staking)
- TypeScript proxy router with Redis
- Fully self-contained HTML dashboards (Tailwind + Chart.js)

## Getting Started
1. Clone the repo or download the HTML files
2. Open `seller-dashboard.html` or `buyer-dashboard.html` in any modern browser

## Project Structure
- `seller-dashboard.html` — Seller interface with wallet connection, key management, and real-time metrics
- `buyer-dashboard.html` — Buyer interface with escrow creation, prompt testing, and spending tracking
- `README.md` — This file

Built for a more open, private, and efficient AI future.