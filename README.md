# 👋 Hi, I'm Chel

I'm a builder on **Base** — Coinbase's Ethereum L2.

![Base](https://img.shields.io/badge/network-Base_mainnet-0052ff?style=flat-square)
![Solidity](https://img.shields.io/badge/Solidity-^0.8.20-363636?style=flat-square&logo=solidity)
![ethers.js](https://img.shields.io/badge/ethers.js-v6-2535a0?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-green?style=flat-square)

I started learning by farming airdrops and ended up actually shipping things on chain.

---

## 📊 Stats

- **5** smart contracts deployed on Base mainnet
- **5** live dApps, all hosted on GitHub Pages
- **All contracts verified** on Sourcify
- **0** lines of `node_modules` — every dApp is a single HTML file

---

## 🛤 My journey

1. Farmed airdrops on a few networks, learned the basics of wallets and transactions.
2. Discovered Base Builders & Founders on Guild.xyz and saw the "Contracts Deployed: 10+" goal.
3. Deployed my first 5 unique Solidity contracts on Base mainnet.
4. Realized I could build an actual frontend on top of one of them — `GuestBook`.
5. One frontend turned into five. All hosted free on GitHub Pages.
6. Now I have a small portfolio of working on-chain experiences anyone can try.

The shift from "airdrop farmer" to "actually shipped something" is small in lines of code,
but huge in mindset.

---

## 🧭 How I build

- **Single-file dApps.** No bundlers, no `node_modules`. Anyone can read the source in 5 minutes.
- **Verify everything.** Every contract is verified on Sourcify so the source is publicly readable.
- **No admin override on user funds.** If a contract holds ETH belonging to a user (Vault), even
  the deployer can't pull it out before the unlock time. Code is the only authority.
- **Free hosting.** GitHub Pages serves all five dApps for $0. No backend, no database.
- **Public by default.** Every interaction is on chain and indexable.

---

## 📌 Pinned project

### [onchain-base](https://github.com/hellblade1488/onchain-base)

> Experiments and tools for building on Base L2.

Five Solidity contracts + five live dApps hosted on GitHub Pages.
Pure HTML/CSS/JS — no build step, no `node_modules`, no frameworks.
Anyone can clone the repo and serve any dApp with `npx serve dapps/<name>`.

Try the **GuestBook** live: [hellblade1488.github.io/onchain-base/dapps/guestbook](https://hellblade1488.github.io/onchain-base/dapps/guestbook/)

---

## 🧱 What I'm building

### Smart contracts on Base mainnet

Five Solidity contracts deployed and verified on Base, each demonstrating a different on-chain primitive:

| Contract | What it does |
|----------|--------------|
| **GuestBook** | Public on-chain guestbook — anyone can sign with a 280-char message |
| **TipJar** | ETH tip jar with optional notes; owner-only withdrawal |
| **SimpleVoting** | Lightweight on-chain polling, one vote per address |
| **TimeLockedSavings** | Per-user ETH lockbox until a chosen unlock time |
| **OnChainTodo** | Personal todo list scoped per address |

→ Full list with addresses and Sourcify verification:
[**CONTRACTS.md**](https://github.com/hellblade1488/onchain-base/blob/main/CONTRACTS.md)

### Live dApps

| dApp | Description | Open |
|------|-------------|------|
| 🟦 **GuestBook** | Sign an immutable 280-char message on chain | [open ↗](https://hellblade1488.github.io/onchain-base/dapps/guestbook/) |
| 💰 **TipJar** | Send ETH on Base with a public note | [open ↗](https://hellblade1488.github.io/onchain-base/dapps/tipjar/) |
| 🗳️ **Voting** | Create polls and vote on chain | [open ↗](https://hellblade1488.github.io/onchain-base/dapps/voting/) |
| 🔒 **Vault** | Time-locked ETH savings with countdown | [open ↗](https://hellblade1488.github.io/onchain-base/dapps/vault/) |
| 📋 **Todo** | Personal todo list, scoped per address | [open ↗](https://hellblade1488.github.io/onchain-base/dapps/todo/) |

[Source ↗](https://github.com/hellblade1488/onchain-base/tree/main/dapps)

---

## 🛠 Tech

- **Solidity** `^0.8.20`
- **ethers.js** v6 (no build step, single-file dApps)
- **Remix IDE** for contract deployment
- **GitHub Pages** for free dApp hosting
- **Base mainnet** (chain id `8453`)

---

## 🚀 What's next

- ERC-20 token with on-chain claim
- Simple NFT mint page (ERC-721 with off-chain metadata pinned to IPFS)
- Multisig wallet experiment (M-of-N signatures)
- A small DEX prototype using a constant-product formula

Same pattern as the existing dApps: one contract, one single-file frontend, hosted free on GitHub Pages.

---

## 📦 Repos

- [**onchain-base**](https://github.com/hellblade1488/onchain-base) — smart contracts and dApps on Base L2

---

## 🌐 On chain

- ⛓️ My address on Base: [`0xF413…58C70`](https://basescan.org/address/0xf41...8c70)
- 📜 GuestBook contract: [`0x7015…999f`](https://basescan.org/address/0x701546B92991CAC01f98c9aaB3AB8C8dd6d1999f)

---

> «The goal is to be a builder.»
