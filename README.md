# SwiftRemit  
**Instant, low-cost cross-border remittances for migrant workers**  
*Money home. Instantly.*

---

## 🌍 Overview

**SwiftRemit** is a mobile-first remittance platform built on **Movement L1** that enables migrant workers to send money home in seconds at near-zero cost — without requiring crypto knowledge.

Using **Privy embedded wallets**, **x402 payment rails**, and **USDC stablecoins**, SwiftRemit removes the friction, delays, and high fees of traditional remittance services like Western Union and MoneyGram.

This project is being built for the **Movement × Replit Hackathon** with a focus on real-world utility, clean UX, and startup viability.

---

## 🚨 The Problem

- 250M+ migrant workers send **$700B+ annually**
- Average fees range from **6–8%**
- Transfers take **hours to days**
- Recipients often face poor FX rates and limited cash-out options

Remittances have become a hidden tax on the world’s poorest families.

---

## 💡 The Solution

SwiftRemit enables:
- ⚡ **Instant cross-border transfers** (2–5 seconds)
- 💸 **<1% total fees**
- 📱 **Mobile-first PWA experience**
- 🔐 **Walletless onboarding** via phone number or email
- 🌍 **Multiple off-ramps** (P2P agents, fintech partners, merchants)

Users never need to understand crypto — SwiftRemit abstracts it all away.

---

## 🏗️ Architecture Overview

PWA (Frontend)
↓
Privy Embedded Wallets (Auth + Signing)
↓
Movement L1 (USDC Transfers + Escrow)
↓
P2P Liquidity Agents / Fintech Off-Ramps

---

## 🧰 Tech Stack

### Frontend
- React / Next.js
- Progressive Web App (PWA)
- Tailwind CSS + shadcn/ui
- Mobile-first responsive design

### Wallet & Auth
- **Privy Embedded Wallets**
- Phone number / email / social login
- Session-based transaction signing

### Blockchain
- **Movement L1**
- USDC stablecoin
- Move smart contracts:
  - Escrow module
  - Agent staking & reputation
  - Fee distribution

### Payments
- **x402 payment rails** for instant settlement

### Backend
- Node.js / Bun
- FX rate engine
- Agent matching & routing
- Notifications (SMS / WhatsApp)

---

## 🔐 Smart Contract Design (Move)

### Core Modules

- **Escrow**
  - Locks USDC during transfer
  - Releases funds upon confirmation
  - Timeout & dispute handling

- **Agent Registry**
  - Liquidity agent staking
  - Reputation scoring
  - Slashing for failed settlements

- **Fees**
  - Protocol fee (0.5–1%)
  - Agent incentives

---

## 🔁 Off-Ramp Strategy (MVP)

SwiftRemit uses a **P2P liquidity model** for the initial launch:

- Local agents stake USDC on-chain
- Escrow smart contracts guarantee safety
- Recipients receive fiat via:
  - Bank transfer
  - Mobile money
  - Cash pickup

This model:
- Requires no upfront licenses
- Works immediately in Nigeria and other emerging markets
- Scales organically with demand

---

## 💸 Revenue Model

- **0.5–1% fee per transfer**
- FX spread (transparent)
- Premium corridors (future)
- Business & API integrations (future)

**Example:**  
1M users × $200/month × 1% = **$24M ARR**

---

## 🧪 MVP Scope (Hackathon)

- US → Nigeria corridor
- USDC-only transfers
- PWA frontend
- Privy wallet onboarding
- P2P agent off-ramp
- One escrow smart contract
- Basic agent reputation system

---

## 🗓️ 2-Week Build Plan

### Week 1
- [ ] Project setup (repo, CI, environment)
- [ ] PWA frontend scaffolding
- [ ] Privy auth & wallet integration
- [ ] Basic send flow UI
- [ ] Movement testnet setup
- [ ] Escrow contract (v1)

### Week 2
- [ ] Agent dashboard
- [ ] Off-ramp escrow flow
- [ ] FX rate display
- [ ] Transaction confirmation UI
- [ ] Demo polish
- [ ] Deployment & testing
- [ ] Hackathon submission

---

## 🧑‍🤝‍🧑 Team

- **Fullstack / Blockchain:** Finisher
- **Frontend / UX:** Nailer
- **Backend / Integrations:** Finisher/Nailer

---

## 🏆 Hackathon Tracks

SwiftRemit is submitted for:
- Best Consumer App
- Best x402 App
- Best App Using Privy Wallets
- People’s Choice

---

## 📍 Roadmap (Post-Hackathon)

- Add UK → Nigeria corridor
- Integrate local fintech off-ramps
- Expand to Philippines & India
- Stablecoin debit cards
- Compliance & licensing partnerships

---

## 📄 Disclaimer

SwiftRemit does not custody fiat funds.  
All fiat payouts are handled by licensed third-party partners or peer-to-peer liquidity agents.

---

## 🤝 Contributing

This project is currently in active development for the hackathon.  
Contributions and feedback are welcome after submission.

---

## 📬 Contact

For questions, partnerships, or demos:  
**Email:** successaje7@gmail.com  
**Twitter/X:** @aj_success

---

**SwiftRemit — Money home. Instantly.**
