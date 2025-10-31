DAGive/
├─ contracts/                     # EVM path (Solidity). See wasm/ for non-EVM.
│  ├─ DonationRegistry.sol
│  ├─ CharityAllowlist.sol
│  ├─ libs/
│  └─ scripts/
├─ wasm/                          # Non-EVM path (e.g., Rust/WASM module skeleton)
│  ├─ Cargo.toml
│  └─ src/lib.rs
├─ frontend/
│  ├─ app/                        # Next.js (App Router)
│  ├─ components/
│  ├─ lib/
│  ├─ public/
│  ├─ package.json
│  └─ .env.example
├─ indexer/
│  ├─ docker-compose.yml
│  ├─ src/                        # small Node/TS listener -> Postgres
│  └─ prisma/
├─ docs/
│  └─ architecture.md
├─ .github/
│  ├─ workflows/
│  │  ├─ ci.yml
│  │  └─ deploy-testnet.yml
│  ├─ ISSUE_TEMPLATE/
│  │  ├─ bug_report.md
│  │  └─ feature_request.md
│  └─ CODEOWNERS
├─ .env.example                   # root env for local dev
├─ .gitignore
├─ LICENSE
├─ SECURITY.md
├─ CODE_OF_CONDUCT.md
├─ CONTRIBUTING.md
└─ README.md
