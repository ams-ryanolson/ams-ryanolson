# Ryan Olson

**Founder and engineer. I build the infrastructure that decides where money can safely go.**

Toronto. Building platforms since 2010, and now building payments the way I always wished they worked.

---

## [Anton Payments](https://antonpayments.com) — *Payout intelligence.*

One API to pay anyone, anywhere: bank, card, mobile money and on-chain. You pick the corridor and currency. Anton picks the rail, and decides in real time whether the payout should move at all.

**What happens on every payout**

| | |
|---|---|
| **Screening** | Every beneficiary checked against OFAC, EU, UK and UN sanctions lists before any money moves. |
| **Velocity** | Merchant-scoped caps by day, month, geography and instrument. |
| **The Anton Engine** | Real-time risk scoring from cross-merchant trust signals, beneficiary history, counterparty reputation and anomaly detection. Approved, held for review, or blocked. |
| **Routing** | Multi-rail delivery: Faster Payments, SEPA, ACH, SWIFT, mobile money and stablecoins across major chains, with live corridor delivery times. |
| **Anton Intelligence** | The same decisioning as a standalone API, for payee registration, instrument screening, payout screening and merchant onboarding. |

**Built for trust from day one.** PII and payment instruments live in an isolated PCI-DSS vault, so the core never stores raw account numbers or identity documents. Idempotent, versioned, webhook-driven, DPoP-bound tokens, maker-checker approvals, with SOC 2, PCI DSS and ISO 27001 programs active.

**Stack:** Go services and orchestration · PostgreSQL · Python for the risk models · TypeScript portals for merchants and operations · Terraform-managed cloud infrastructure.

[Docs](https://docs.antonpayments.com) · [antonpayments.com](https://antonpayments.com)

---

## [Real Adult Media](https://www.realadult.media) — *Communities for adults.*

Social networks where each community is its own place, with its own people, its own rules and its own name. They all run on **narwhal**, one platform built to carry many brands, live today as [realkink.men](https://www.realkink.men), the social network for men into kink since 2010, with pup.space and furrow.social coming.

**Under the hood**

| | |
|---|---|
| **Platform** | Laravel and PHP 8.4, Inertia with React and TypeScript, Tailwind. Profiles, circles, events, messaging, a journal and a full moderation desk, in seven languages. |
| **Apps** | Expo and React Native on iPhone, iPad and Android. Native push, CallKit calling, over-the-air updates. |
| **Real time** | Live video rooms, one-to-one calls inside messages, and On Air broadcasting from a phone. WebRTC, Agora and Laravel Reverb. |
| **Media** | An FFmpeg pipeline in Docker for every photo and video members upload. |
| **Billing** | A recurring billing engine we run ourselves, with the card processor only processing. |
| **Infrastructure** | DigitalOcean, Docker, MySQL, Valkey, Horizon queues, Nightwatch monitoring. |

**Open source:** [photo-metadata](https://github.com/realadultmedia/photo-metadata), which strips location and owner data from photos without re-encoding, and [expo-face-boxes](https://github.com/realadultmedia/expo-face-boxes), on-device face detection for Expo.

---

[antonpayments.com](https://antonpayments.com) · [realadult.media](https://www.realadult.media) · Toronto, Canada
