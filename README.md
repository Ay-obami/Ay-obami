# Oyebisi Ayobami

### Solidity / DeFi Protocol Engineer — Freelance • Contract • Part-time

I build security-focused smart contracts and protocol infrastructure for systems where mistakes move money: lending markets, redemptions, treasury execution, escrow, cross-chain verification, oracle-bound logic, and zero-knowledge authorization.

My strongest stack is **Solidity + Foundry**, with TypeScript/Node.js and React/Next.js when a protocol also needs services, operator tooling, or a usable client. I care about explicit trust boundaries, adversarial testing, reproducible deployments, and documentation that says what is actually verified.

**Available for:** smart-contract implementation, DeFi protocol work, contract debugging/refactoring, Foundry test suites, security hardening, deployment/release work, and Web3 integration.

---

## Flagship protocol work

### [Modular Lending & Borrowing Protocol](https://github.com/Ay-obami/Lending_Borrowing_Protocol)

A shared-core Solidity lending market supporting supply, withdrawal, collateralized borrowing, repayment, full-debt liquidation, reserve-level risk controls, variable interest, and Chainlink pricing.

**Engineering evidence:** native-token decimal handling, scaled debt/deposit accounting, collateral-lock isolation, directional rounding, stale/incomplete/future oracle checks, exact-receipt guards, fuzz tests, action-sequence invariants, varied-index lifecycle tests, CI, and a React/wagmi client.

---

### [Clearline — RWA Redemption & Custody Attestation](https://github.com/Ay-obami/Clearline)

An RWA redemption pipeline connecting an on-chain burn/lock event to off-chain asset release through finality checks, redemption-time compliance, threshold EIP-712 authorization, manual-review controls, and on-chain settlement attestations.

**Engineering evidence:** v2 signer/board rotation, deployment-manifest verification, signer/custodian service regressions, local-chain rotation + settlement rehearsal, production frontend build gates, and a historical Blockscout-verified HSK testnet v1 deployment. The repository clearly separates historical v1 evidence from unreleased v2.

---

### [Fair Witness — Trust-Minimized Execution for Autonomous Financial Agents](https://github.com/Ay-obami/fair-witness)

An autonomous-finance architecture where AI can decide **EXECUTE or WAIT**, but deterministic smart-contract policy remains the authority over treasury capital.

**Engineering evidence:** user-owned treasuries, bounded strategies, replay/rate/slippage controls, cross-chain Attestcoin evidence verification, adversarial test coverage, operator/security documentation, and a controlled public-testnet demonstration using real cross-chain transactions, real proofs, Creditcoin verification, and policy-constrained execution.

Live app: https://fair-witness.vercel.app/

---

### [ShadowEscrow — Private Funded Escrow on Midnight](https://github.com/Ay-obami/shadow-escrow)

A Compact/Midnight escrow where payment terms and lifecycle state are public while the approval credential remains private state.

**Engineering evidence:** Created → Funded → Approved → Settled lifecycle, expiry refund/cancel paths, exact native-asset funding, private witness commitment, replay/deadline guards, account-scoped wallet state, generated ZK artifacts, 38 regression tests, CI, and local end-to-end funded lifecycle verification. Historical Preview v1 evidence is preserved separately from v2.

---

## Additional protocol work

- [CrossOdds](https://github.com/Ay-obami/CrossOdds) — cross-chain protocol work with explicit verification boundaries and documented live-RPC limitations.
- [Cipher_Mint](https://github.com/Ay-obami/Cipher_Mint) — ZK/Groth16 verification flow with real proof fixtures and negative-path contract tests.
- [Veil](https://github.com/Ay-obami/veil) — attributed FCC orderbook extension work covering FTSO-aware matching, ZK solvency verification, balance persistence, race testing, and a bounded offline reproducibility path.
- [Undertow](https://github.com/Ay-obami/Undertow) — Flare/Coston2 lending integration and research branch kept separate from the canonical lending core.
- [Baseline](https://github.com/Ay-obami/Baseline) — Canton/Daml subscription-credit facility prototype with reproducible Daml tests and DAR build.

---

## What I bring to a protocol team

- **Solidity architecture:** state machines, modular protocols, access control, EIP-712, ERC integrations, custody and settlement flows
- **DeFi mechanics:** lending/borrowing, liquidations, interest/index accounting, collateral controls, treasury execution, vault-like flows
- **Testing & security:** Foundry unit/fuzz/invariant testing, adversarial scenarios, replay protection, authorization boundaries, failure-path analysis
- **Oracles & cross-chain:** Chainlink validation, FTSO-aware logic, proof/evidence verification, finality-aware workflows
- **Privacy / ZK:** Groth16 verifier integration, Compact/Midnight private witnesses, public/private state boundary design
- **Delivery:** CI gates, deployment scripts, release runbooks, migration constraints, frontend/backend integration when needed

I prefer protocol designs with explicit assumptions and testable state transitions. For capital-sensitive actions, I favor deterministic on-chain enforcement over trusting off-chain software to behave correctly.

---

## Core stack

**Solidity · Foundry · EVM · Chainlink · TypeScript · Node.js · React · Next.js · wagmi · viem · Rust/Soroban · Daml/Canton · Circom/Groth16 · Midnight/Compact**

---

## Work with me

I am intentionally open to **freelance, contract, agency-subcontracting, and part-time Web3 work**.

The fastest way to evaluate fit is to send me one of these:

- a protocol specification that needs implementation;
- a Solidity repo that needs debugging or hardening;
- a failing Foundry test suite;
- a DeFi feature that needs architecture + tests;
- a deployment/integration problem with a concrete target network.

**Email:** [oyebisiayobami26@gmail.com](mailto:oyebisiayobami26@gmail.com)  
**GitHub:** [@Ay-obami](https://github.com/Ay-obami)
