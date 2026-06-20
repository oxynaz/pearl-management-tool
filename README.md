# Pearl Management Tool (PRL)

> **One-command manager to set up and run Pearl (PRL) mining — made by the [PulseMining](https://discord.gg/BKFaXmZ2Az) community.**
> Independent community tool. Not affiliated with or endorsed by Pearl Research Labs.

![Tool](https://img.shields.io/badge/type-mining%20manager-8a2be2)
![Languages](https://img.shields.io/badge/languages-EN%20·%20FR%20·%20ES%20·%20RU-blue)
![Mining](https://img.shields.io/badge/mining-GPU-brightgreen)
![Coin](https://img.shields.io/badge/coin-Pearl%20(PRL)-orange)

---

## What is Pearl (PRL)?

Pearl is a **Layer-1 blockchain** (forked from Bitcoin's `btcd`) that replaces traditional hashing with **Proof-of-Useful-Work**: instead of computing meaningless hashes, miners run large-scale **matrix multiplication on NVIDIA GPUs** — the same arithmetic that powers AI training and inference. The reference miner is built on the **vLLM** inference framework, the design is grounded in a peer-reviewed paper, and the stack includes post-quantum signatures (XMSS) and a zero-knowledge proof-of-work verifier (Plonky2). Mainnet launched in April 2026; the native token is **PRL**.

**Official project (not us):** [github.com/pearl-research-labs/pearl](https://github.com/pearl-research-labs/pearl) — by Pearl Research Labs

This repository is an **unofficial, community-built helper tool**.

---

## What this tool does

`PEARL_MANAGER` is a single menu-driven program that automates the Pearl setup. You launch it, pick your language, and use the menu:

- 📦 **Install / set up the node**
- 👛 **Wallet** — create and manage your Pearl address
- ⛏️ **Start mining** (GPU)
- 🌍 **Multilingual** — English, Français, Español, Русский

<!-- Add a screenshot of the menu here once the repo is up: -->
<!-- ![PEARL_MANAGER menu](doc/menu.png) -->

---

## Requirements

- A **capable NVIDIA GPU** with CUDA — Pearl mining is GPU-intensive (large matrix-multiplication / AI-style workloads)
- **Linux** (tested on Ubuntu 24.04)
- A Pearl wallet address — the tool helps you set one up

---

## Download & run

Download the latest `PEARL_MANAGER` from the [**Releases**](https://github.com/oxynaz/pearl-management-tool/releases) page, then:

```bash
chmod +x PEARL_MANAGER
./PEARL_MANAGER
```

Pick your language, then follow the menu.

> **Verify your download** before running:
> ```bash
> sha256sum PEARL_MANAGER
> ```
> Expected: `d3f90293c91b239fe619b51b8736280440f1e5bbcc08deb9b6d31053262576e3`
>
> Heads-up: GPU miners are sometimes flagged by antivirus as PUA — add an exclusion for the miner file rather than disabling protection.

---

## Why mine with PulseMining?

PulseMining is a crypto-**mining** community built around one idea: getting onto new mineable coins **early**, with the tooling and support that make it painless.

- 🧰 **Ready-made managers like this one** — install, wallet and mining in a few keystrokes, no manual setup marathon
- 🌍 **Real-time multilingual community** (FR · EN · ES · RU) — follow everything, whatever your language
- 🛟 **Responsive support** — stuck miner, wallet question, driver issue? Someone's there
- 🔎 **Early on new coins** — we find new mineable projects and get them running fast, with exclusive tools you won't find elsewhere

No promises of riches — just the tools, the people, and a head start.

### 👉 Join PulseMining: **https://discord.gg/BKFaXmZ2Az**

---

## Disclaimer

This is an **unofficial, community-made tool**, not affiliated with or endorsed by Pearl Research Labs. It is a binary utility that automates installing and running third-party mining software on your machine — review it and your setup before use. Mining and holding cryptocurrencies is **speculative and carries risk**, and Pearl mining profitability in particular can change quickly with network difficulty and the PRL price. Nothing here is financial advice or a promise of any return. Use at your own risk, and check the [official Pearl project](https://github.com/pearl-research-labs/pearl) and your local regulations.
