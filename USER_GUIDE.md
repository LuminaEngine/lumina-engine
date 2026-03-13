# Lumina Engine — User Guide

**Welcome to Lumina Engine (Beta)**

Lumina is a private trading interface where your intent is shielded, execution is private, and settlement is atomic.

> **Quick start:** Connect wallet → take the tour → claim test tokens → do a small swap → try a limit order → send feedback.

---

## Table of Contents

1. [Before You Start](#1-before-you-start)
2. [Landing Page](#2-landing-page)
3. [Guided Tour](#3-guided-tour-7-steps)
4. [Main Trade Screen](#4-main-trade-screen)
5. [Connect Your Wallet](#5-connect-your-wallet)
6. [Claim Test Tokens](#6-claim-test-tokens)
7. [Make Your First Swap](#7-make-your-first-swap)
8. [Place a Limit Order](#8-place-a-limit-order)
9. [Transfer Between Wallets](#9-transfer-between-wallets)
10. [Activity & Tracking](#10-activity--tracking)
11. [Troubleshooting](#11-troubleshooting)
12. [Feedback](#12-feedback)

---

## 1. Before You Start

### What you need

- A supported wallet (the **Connect** button in the top right shows what's supported)
- A stable internet connection
- 5 minutes

### Beta expectations

You may encounter UI polish issues, token list gaps, or temporary liquidity constraints. If something breaks, that's why you're here — please report it.

### If you get stuck

Reach out on the beta testing group: [Lumina Beta Testing](https://t.me/+6606n-1YqLE1MzU0)

---

## 2. Landing Page

When you open [beta.luminaengine.ai](https://beta.luminaengine.ai), you'll see:

- A welcome screen with the positioning: *Private, atomic settlement for digital assets*
- Two options:
  - **Take the Tour** — recommended, 7 quick steps
  - **I'll explore on my own**

---

## 3. Guided Tour (7 Steps)

### Step 1 — Privacy First
Your trading intent is protected by zero-knowledge proofs. Others can't see your order sitting in the open like a snack for MEV bots.

### Step 2 — Instant Swap
Market-rate swaps execute immediately. You get a result without waiting around or relying on a counterparty.

### Step 3 — Limit Orders
Set a price and leave it. Orders can have an expiry window (1 to 30 days).

### Step 4 — Choose What to Sell
Select the asset you're selling and the amount. Quick-fill shortcuts: **25% / 50% / 75% / Max**.

### Step 5 — What You'll Receive
See estimated proceeds updating in real time based on available liquidity.

### Step 6 — Private Execution
Trades execute privately with zero information leakage. Your positions stay invisible to the market.

### Step 7 — Your Dashboard
Navigate using the bottom bar: **Trade · Transfer · Claim · Activity**

Tap **Start Trading** to begin.

---

## 4. Main Trade Screen

### Status bar
- `Intent shielded · ready`
- `Visibility: Only you`

### Trade modes
| Mode | Description |
|---|---|
| **Swap** | Instant market-rate exchange |
| **Limit** | Set a target price and expiry |

### Trade inputs
- **Sell** — select asset and enter amount
- **Buy** — select asset to receive
- Swap direction button (up/down arrows between Sell/Buy)

### Trade info
- **Rate** — current indicative exchange rate
- **Execution** — `Private · 0 exposed`
- **Max slippage** — adjustable (default 0.50%)

---

## 5. Connect Your Wallet

1. Tap **Connect** (top right) or **Connect Wallet** on the trade card
2. Select your wallet:
   - **Miden Wallet** — [download here](https://midenbrowserwallet.com/) if not already installed
   - Or create a new wallet directly in the Lumina app
3. Approve the connection in your wallet
4. Return to the app

**Success looks like:**
- The Connect button updates to show your wallet state
- Token selectors become available and balances populate

If you connect and still see zeros, see [Troubleshooting](#11-troubleshooting).

---

## 6. Claim Test Tokens

*Recommended first action for beta testing.*

1. Tap **Claim** in the bottom navigation
2. Claim available test tokens
3. Return to **Trade**

**Success looks like:**
- Wallet balance updates
- Tokens become selectable in Sell/Buy

---

## 7. Make Your First Swap

Start small — you're testing the system.

1. Go to **Trade → Swap**
2. Under **Sell**, tap **Select** and choose a token
3. Enter a small amount
4. Under **Buy**, choose the token you want to receive
5. Review:
   - Estimated receive amount
   - Slippage limit
   - Execution status shows **Private**
6. Confirm the trade
7. Approve any wallet prompts

**Success looks like:**
- An entry appears in Activity
- Balances adjust accordingly

---

## 8. Place a Limit Order

1. Go to **Trade → Limit**
2. Select **Sell** token and amount
3. Select **Buy** token
4. Set your **limit price**
5. Set an **expiry** if prompted
6. Submit order

**Success looks like:**
- Order appears in **Activity** as open/active
- Stays visible until filled or expired

---

## 9. Transfer Between Wallets

1. Tap **Transfer** in the bottom navigation
2. Choose:
   - Token
   - Amount
   - Destination wallet address *(double-check — copying addresses manually is error-prone)*
3. Confirm and approve in wallet

**Success looks like:**
- Transfer logged in **Activity**
- Balances update

---

## 10. Activity & Tracking

Tap **Activity** to review:

- Swaps
- Limit orders (open / filled / expired)
- Transfers
- Claims

If something feels missing, screenshot it and include it in your feedback.

---

## 11. Troubleshooting

### Connect Wallet doesn't work
- Refresh the page
- Try a different browser (Safari can be temperamental)
- Disconnect and reconnect your wallet

### Balances show 0.00
- Confirm you're on the expected network
- Go to **Claim** first and claim test tokens
- Refresh after claiming

### Token not in the list
- Note the token name and what you searched
- Submit feedback — this helps us improve coverage

### Swap quote doesn't appear
- Could be a liquidity or token-pair issue
- Try a different pair or a smaller amount
- Capture a screenshot of the state

### Transaction stuck or pending
- Check your wallet's pending queue
- Check network conditions
- If it fails, include the error message in your feedback

---

## 12. Feedback

Lumina is in active beta — your feedback directly shapes the product.

**Feedback form (1 min):** [Lumina Beta Feedback & Bug Reports](https://forms.gle/ZbiTb57QXHSwYHZq6)

When reporting, please include:

| Field | Example |
|---|---|
| What you were trying to do | "Swap USDC → ETH" |
| What you expected | "See a quote and confirm swap" |
| What actually happened | "Quote stayed blank / button disabled" |
| Where it happened | Trade / Limit / Claim / Transfer / Activity |
| Screenshots | Paste any error states |
| Device + browser | iPhone 15 / Safari |

---

## First Test Checklist

Use this to verify the core flows are working:

- [ ] Open app at [beta.luminaengine.ai](https://beta.luminaengine.ai)
- [ ] Take the guided tour
- [ ] Connect wallet (Miden wallet or Lumina wallet)
- [ ] Claim test tokens
- [ ] Do a small swap
- [ ] Place a limit order
- [ ] Send a private transfer
- [ ] Request a payment
- [ ] Check activity log
- [ ] Submit feedback

---

*For technical documentation, API reference, and architecture details, see the [developer documentation](./docs/).*
