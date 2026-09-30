# $STREAM — Point of No Return

> **1B existed. 699.99M was burned. But the number that closes the case is 0.**

**Point of No Return** is a short, evidence-first interactive investigation of the historic $STREAM supply burn.

Instead of asking users to read an announcement, it makes them reconstruct the event themselves — then verify the real Solana transaction on-chain.

**3 decisions · ~30 seconds · 1 verifiable transaction**

---

## 🎮 Live Investigation

### [Launch Point of No Return →](https://stream-point-of-no-return.netlify.app)

No wallet connection. No signup. No prior knowledge of $STREAM required.

---

## The Case

$STREAM began with a total supply of **1 billion tokens**.

The Streamflow Foundation reported burning its **entire $STREAM holding — 699.99M tokens — in a single Solana transaction**.

That represented approximately **70% of the original supply**, leaving approximately **300M $STREAM** across the network.

But there is an important distinction:

> **~300M = network supply remaining**  
> **0 = Foundation $STREAM holding remaining after burning its entire position**

Point of No Return turns that distinction into an interactive investigation instead of simply giving users the answer.

---

## How It Works

The experience follows a simple investigation loop:

**Evidence → Decision → Explanation → Proof**

### 01 — Reconstruct the Supply

The player starts with:

- Original network supply: **1B $STREAM**
- Published post-burn supply: **~300M $STREAM**

Using an interactive supply model, the player reconstructs the approximate percentage removed.

**Answer: ~70%**

Wrong estimates do not simply return “incorrect.”  
They explain what supply would remain and point the player back to the evidence.

---

### 02 — Understand What “Burned” Means

The player must distinguish between:

**Locked** — tokens still exist but temporarily cannot move.

**Vested** — tokens still exist and become available according to a future schedule.

**Burned** — tokens are permanently removed from supply.

### Why burn it?

To permanently remove the Foundation's future control over those tokens.

Locked tokens can become available later.  
Vested tokens unlock over time.  
Burned tokens cannot return, unlock, or be released later.

---

### 03 — Close the Case

The final evidence screen gives the player:

- **1B** original network supply
- **699.99M** published burn
- **~300M** post-burn network supply
- **1** Solana transaction
- **Permanent** burn
- **Entire Foundation holding** burned

Then it asks:

> If approximately 300M $STREAM still existed across the network, what remained in the Foundation's own $STREAM holding?

# **0 $STREAM**

The player then reaches the actual on-chain proof.

---

## Why This Is Different

### Evidence-first, not trivia-first

This is not a conventional token quiz.

Every decision is connected to evidence, and the player reconstructs the event rather than memorizing a fact.

### Wrong answers are part of the experience

Incorrect choices explain the misconception.

For example:

- **300M** is the remaining network supply, not the Foundation balance.
- **699.99M** is the amount burned, not the amount remaining.
- **~70%** is the burn ratio, not a token balance.
- **Locked** and **vested** tokens still exist; burned tokens do not return.

### Built for zero prior knowledge

The experience assumes the player knows nothing about $STREAM, token burns, vesting, or token locks.

Technical concepts are explained when they become relevant.

### Verification is part of the product

The investigation does not end with a score.

It ends with the real Solana transaction.

> **Claim → Evidence → Understanding → On-chain Proof**

---

## 🔎 Verify the Burn

**Published burn:** 699.99M $STREAM  
**Approx. original supply removed:** ~70%  
**Published post-burn supply:** ~300M $STREAM  
**Execution:** Single Solana transaction  
**Mechanism:** Permanent burn  
**Foundation holding after burning its entire position:** 0 $STREAM

### Transaction Signature

```text
4rbViHbmCV35ttMngeC8KBULCMctD7X8mNg3RxfvGwPKyPi7hX8VKpjyJ81AnYuVzzXEsWuNuppcpDY47hnchZNv
```

### [Verify on Solscan →](https://solscan.io/tx/4rbViHbmCV35ttMngeC8KBULCMctD7X8mNg3RxfvGwPKyPi7hX8VKpjyJ81AnYuVzzXEsWuNuppcpDY47hnchZNv?cluster=)

> **Don't trust the interface. Verify the evidence.**

---

## What the Player Learns

By the end of the investigation, the player can distinguish four numbers that describe different parts of the same event:

| Evidence | Meaning |
|---|---|
| **1B $STREAM** | Original network supply |
| **699.99M $STREAM** | Published burn amount |
| **~300M $STREAM** | Published post-burn network supply |
| **0 $STREAM** | Foundation holding after burning its entire position |

This distinction is the core of the experience.

---

## Experience Flow

```text
OPEN THE CASE
      ↓
1B ORIGINAL SUPPLY
      ↓
RECONSTRUCT THE BURN
      ↓
LOCKED vs VESTED vs BURNED
      ↓
UNDERSTAND PERMANENCE
      ↓
READ THE FINAL EVIDENCE
      ↓
699.99M → 0
      ↓
VERIFY ON SOLANA
```

---

## Design Principles

**Fast to understand**  
The investigation contains only three decisions and is designed to be completed in roughly 30 seconds.

**Learn by doing**  
Core concepts are discovered through interaction instead of a long article.

**Meaningful failure**  
Wrong answers explain why the interpretation does not match the evidence.

**Low friction**  
No wallet, signup, installation, or prior Web3 knowledge is required.

**Verification over trust**  
The final destination is the underlying on-chain transaction.

---

## Built With

- HTML5
- CSS3
- Vanilla JavaScript
- Solana on-chain proof
- Solscan verification
- Netlify

The application is intentionally lightweight:

- No framework
- No backend
- No wallet connection
- No account required

Everything runs client-side.

---

## Run Locally

Clone the repository:

```bash
git clone https://github.com/rosakarimi121/stream-point-of-no-return.git
```

Enter the project:

```bash
cd stream-point-of-no-return
```

Open:

```text
index.html
```

in any modern browser.

---

## Project Structure

```text
stream-point-of-no-return/
├── index.html
└── README.md
```

The minimal architecture keeps the project easy to inspect, run, and maintain.

---

## Numbers & Rounding

The published figures describe a burn of **699.99M $STREAM** from an original **1B supply**.

699.99M / 1B = **69.999%**, conventionally represented as approximately **70%**.

For that reason, the experience uses **~300M** when referring to the published post-burn network supply where appropriate.

---

## Why “Point of No Return”?

Locking changes **when** tokens can move.

Vesting changes **when** tokens become available.

A permanent burn changes whether the burned tokens can ever return at all.

That irreversible boundary is the:

# **Point of No Return.**

---

## Links

**Live Experience:**  
https://stream-point-of-no-return.netlify.app

**On-chain Proof:**  
https://solscan.io/tx/4rbViHbmCV35ttMngeC8KBULCMctD7X8mNg3RxfvGwPKyPi7hX8VKpjyJ81AnYuVzzXEsWuNuppcpDY47hnchZNv?cluster=

---

### Don't trust the game. Verify the burn on-chain.
