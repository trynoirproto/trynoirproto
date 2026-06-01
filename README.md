# Noir Protocol

The matching engine for tokenized equities.

Trillions of dollars of stocks, ETFs, and real-world assets are moving onchain. They need a real market — not a bonding curve.

## What we build

| Repo | Description |
|---|---|
| [matching-engine](https://github.com/noirproto/matching-engine) | Central limit order book. Price-time priority. Off-chain matching at hardware speed. |
| [noir-sdk](https://github.com/noirproto/noir-sdk) | TypeScript SDK — place orders, read the book, verify settlements. |
| [settlement-contracts](https://github.com/noirproto/settlement-contracts) | On-chain settlement. Non-custodial, sign-to-move. |
| [order-log](https://github.com/noirproto/order-log) | Public append-only log of every order the engine processes. |
| [noir-cli](https://github.com/noirproto/noir-cli) | Terminal interface for the protocol. |
| [awesome-tokenized-equities](https://github.com/noirproto/awesome-tokenized-equities) | Curated ecosystem resources. |

## How it works

Orders are signed messages — your wallet signs offchain, for free. The engine matches at hardware speed by price-time priority. The instant two orders cross, settlement fires onchain. T+0.

Your funds never touch us. Nothing moves unless you signed for it.

Every order the engine sees is written to a public log. You can replay it and prove the matching was fair.

**The code is the proof.**
