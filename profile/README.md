<p align="center">
  <img src="https://www.moongate.one/moongate.svg" alt="MoonGate" width="120" />
</p>

<h1 align="center">MoonGate</h1>

<p align="center">
  <strong>Trade all of Solana in one click.</strong>
</p>

<p align="center">
  <a href="https://moongate.one">Website</a> •
  <a href="https://web.moongate.one">Web App</a> •
  <a href="https://docs.moongate.one">Docs</a> •
  <a href="https://x.com/onemoongate">Twitter</a>
</p>

---

## What is MoonGate?

MoonGate is a Solana-native trading platform that makes crypto accessible to everyone. Social login, MPC wallets, gasless swaps, fiat onramps — no seed phrases, no gas headaches, no friction.

**For users:** Trade any token on Solana from your phone or browser. Buy with a card. Swap instantly.

**For developers:** Drop our SDK into your dApp and give your users social login + embedded wallets in minutes.

## Products

| Product | Description |
|---|---|
| **[Mobile App](https://web.moongate.one)** | iOS, Android & Web — swipe-to-trade, token analytics (TRACKR), coin discovery (FALCON) |
| **[MoonSuite Widget](https://docs.moongate.one)** | Embeddable trading widget for partner sites — white-labeled, rev-share enabled |
| **[Partner Dashboard](https://docs.moongate.one)** | Analytics, API keys, fee config, referral tracking, airdrop campaigns |

## Developer SDKs

### Moongate Adapter
> Drop-in Solana Wallet Standard adapter. Social login for any dApp.

```bash
npm install @moongate/moongate-adapter
```

```typescript
import { MoongateWalletAdapter } from "@moongate/moongate-adapter";

const adapter = new MoongateWalletAdapter();
```

📦 [moongate-adapter](https://github.com/onemoongate/moongate-adapter) • [Docs](https://docs.moongate.one/authentication/moongate-adapter/overview)

### Solana Wallet SDK
> Low-level SDK for MPC wallet operations, transaction signing, and auth flows.

```bash
npm install @moongate/solana-wallet-sdk
```

📦 [solana-wallet-sdk](https://github.com/onemoongate/solana-wallet-sdk)

## Architecture

- **Auth:** Social login (Google, Apple, X, Telegram, Ethereum) → MPC wallet (no seed phrases)
- **Trading:** Jupiter, Raydium, Pump.fun — smart routing across all Solana DEXs
- **Onramp:** Fiat-to-crypto via MoonPay + Onramper (global coverage)
- **Infra:** TypeScript monorepo, React Native (Expo), Next.js, Fly.io, Supabase

## Links

| | |
|---|---|
| 🌐 Website | [moongate.one](https://moongate.one) |
| 📱 App | [web.moongate.one](https://web.moongate.one) |
| 📚 Docs | [docs.moongate.one](https://docs.moongate.one) |
| 🐦 Twitter | [@onemoongate](https://x.com/onemoongate) |
| 💬 Telegram | [@and_its_praneet](https://t.me/and_its_praneet) |
| 📧 Contact | dev@moongate.one |
| 📅 Book a call | [Calendly](https://calendly.com/moongate-founders/30min) |

---

<p align="center">Built in UAE 🇦🇪 • Backed by Entrepreneur First</p>
