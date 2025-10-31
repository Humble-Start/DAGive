# DAGive
DAGive is an open-source dApp for charitable giving on a DAG-structured Layer-1. It supports donor-advised flows, charity allowlists, tax-friendly receipts, and micro-donations enabled by low fees and fast confirmations. Includes contracts (or WASM modules), an indexer, a Next.js front end, and CI workflows to deploy to testnet.

## Features
- Charity allowlist with on-chain verification
- Micro-donations & batching (great for low-fee DAG chains)
- On-chain donation receipts + indexed dashboard
- Gas sponsorship / meta-tx (optional)
- Next.js frontend + lightweight indexer

## Quick start
1. Clone: `git clone https://github.com/<you>/DAGive && cd DAGive`
2. Copy env: `cp .env.example .env` and `cp frontend/.env.example frontend/.env`
3. Choose your path:
   - **EVM DAG L1:** compile Solidity in `contracts/`, deploy via scripts.
   - **Non-EVM/WASM:** use `wasm/` module skeleton and your chain’s SDK.
4. Run frontend: `cd frontend && npm i && npm run dev`

See `docs/architecture.md` for details.
