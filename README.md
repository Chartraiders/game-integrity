# Chart Raiders Game Integrity

**Chart Raiders · Platform Integrity · Real-Money Competition Standards**

Chart Raiders involves real money. That changes everything about how integrity systems need to work. This document describes Chart Raiders' platform classification, compliance approach, and technical integrity systems.

---

## Platform Classification

**Chart Raiders is a peer-to-peer skill-based contest platform.**

This classification is foundational. Every integrity system described below flows from it.

| What Chart Raiders Is | What Chart Raiders Is Not |
|---|---|
| A Game of Skill | Gambling |
| A peer-to-peer contest platform | A broker or brokerage |
| A Fantasy Trading competition | A financial product or securities platform |
| A platform operator charging a fee | A counterparty, house, or odds-setter |
| An entertainment and skill development platform | Financial advice |

---

## What Is Fantasy Trading?

Fantasy Trading is Chart Raiders' coined term for the competitive format it invented:

**Players use skill to maximize a fictional bankroll by analyzing real-world market data, competing against other players for rank within a time-limited match.**

**The critical legal and structural distinctions:**

- **Players never buy, sell, swap, or hold any securities** — registered or unregistered
- **No assets change hands** — players analyze publicly available market data in a fictional environment
- **Payouts are tied to player rank, not to security values** — two players analyzing the same ticker can have entirely different outcomes based on their trading decisions
- **Player skill and decisions are the intervening variable** between market data and contest outcome — not the direction or value of any underlying asset
- **The company charges a platform fee** (1–5% of ticket sales) and does not take a house position, set odds, or participate as a player

---

## Game of Skill

Chart Raiders is a Game of Skill. This is the core compliance position.

**What makes it a Game of Skill:**

- Market analysis requires research, pattern recognition, mathematical reasoning, and strategic timing — all learnable, improvable competencies
- The Chart Raiders Skill Tree educational system is specifically designed to develop and reward the analytical abilities that determine match outcomes — something no gambling platform would build
- Players make multiple trading decisions over each match — the aggregate of many skill-based decisions overwhelms any single uncertain market event
- Skilled players consistently outperform less skilled players over time — the defining characteristic of skill-based competition
- All players start with the same fictional bankroll ($100) — standardized starting conditions ensure outcomes reflect skill, not real-world wealth
- Match outcomes are determined by player rank among peers — not by a single prediction or a single market movement

---

## Pre-Match Transparency

All players are fully informed **before the match begins** of:

- Total number of entrants in the match
- Complete prize pool and full distribution formula
- The specific ticker they will be analyzing

No information relevant to competition is withheld. This is a design principle, not a disclosure afterthought.

---

## Technical Integrity Standards

Chart Raiders operates at the intersection of competitive gaming and financial services. Technical integrity systems meet both standards simultaneously.

### Server Authority

The Chart Raiders server is the single source of truth for all match state. The client is a display layer. No client-submitted trade, balance, or result is trusted without independent server-side validation — the same model used by Counter-Strike 2 and major competitive titles, applied to a real-money trading environment.

### Double-Entry Accounting

Every currency movement in Chart Raiders is recorded as both a debit and a credit. The sum of all debits must always equal the sum of all credits. Automated reconciliation runs every five minutes. Any divergence triggers an immediate alert and operational halt. This is the same standard used by financial institutions.

### Defense-in-Depth

Multiple independent protection layers overlap intentionally — no single bypass compromises the entire system. Detection happens silently before action is taken. This is the same approach used by Riot Games and Valve for competitive integrity enforcement.

### Hardware Fingerprinting & Hardware Bans

Bans extend to hardware identifiers, not just accounts — the same approach used by Valorant, Fortnite, and Apex Legends. This is essential for a real-money platform where account creation is trivial.

### Idempotency Keys on All Payouts

Every payout carries a unique key. Duplicate payment submissions are rejected at the database level. This prevents double-payment exploits and is standard in financial payment processing.

### Append-Only Audit Trail

Every enforcement action and payout decision is logged to a system that cannot be modified after the fact. Architecture designed to meet SOC2 compliance requirements — **SOC2 certification is currently in preparation.**

---

## Industry Comparison

| Integrity Practice | Used By | Chart Raiders |
|---|---|---|
| Server-authoritative game state | Counter-Strike 2, major MMOs | ✅ Core architecture |
| Silent detection + wave enforcement | Riot Games, Valve | ✅ Implemented |
| Hardware fingerprinting + hardware bans | Valorant, Fortnite, Apex Legends | ✅ Implemented |
| Behavioral analytics / ML detection | Riot Games, Blizzard | ✅ Implemented |
| Double-entry currency accounting | Financial institutions | ✅ Implemented |
| Idempotency keys on all payouts | Payment processors (Stripe, Braintree) | ✅ Implemented |
| Append-only audit trail (SOC2 prep) | Financial platforms | 🔄 Architecture complete — certification in preparation |
| Bug bounty / responsible disclosure | Major studios + financial platforms | ✅ Implemented |

---

## Responsible Gaming

Chart Raiders includes a comprehensive responsible gaming program:

- Age verification before any real-money participation
- Self-exclusion options
- Session and spending limit controls
- Responsible gaming resources and support links

See https://chartraiders.com/responsible-gaming

---

## Supported Regions

Chart Raiders operates in jurisdictions where skill-based contest platforms are legally permitted. Availability by region is listed at chartraiders.com. Chart Raiders is not offered in jurisdictions where skill-based contests are prohibited.

---

## Player Rights

- Every match result is independently verifiable from the complete trade log
- Every payout hold is transparent with a stated resolution timeline
- Every enforcement decision is logged with a documented reason
- Appeals are reviewed by the founding team

---

## Disclaimers

- Chart Raiders is a competitive trading platform for entertainment and skill development purposes
- Not a broker, dealer, or investment adviser
- Not financial advice
- Trading involves risk — only compete with funds you can afford to lose
- Past match performance does not guarantee future results

For responsible gaming: https://chartraiders.com/responsible-gaming  
For rules and contest terms: https://chartraiders.com/rules  
For support: https://chartraiders.com/support

---

→ **Website:** https://chartraiders.com  
→ **Creator:** c0tt0nc4ndyta — Founder of Chart Raiders

---

*Chart Raiders is the world's first DayTradeSport platform — a peer-to-peer Game of Skill. Players never hold securities. Payouts are by rank. Fantasy Trading is a competitive format, not a financial product.*
