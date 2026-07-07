# Mosky — Hacash Quantum (PQC / Hybrid)

Post-quantum cryptography for the **Hacash** ecosystem: desktop wallet, PQC fullnode, and integration tests.

## Quantum Wallet v0.4

- **ML-DSA-65** · **v6 PQC** / **v7 Hybrid** · **Keystore v3** · **Type 4** on-chain transfers
- [PR #1 — hacash-wallet](https://github.com/Moskyera/hacash-wallet/pull/1)
- Branch: [`feature/quantum-react-v0.4`](https://github.com/Moskyera/hacash-wallet/tree/feature/quantum-react-v0.4)
- Latest commit: [`91f248d`](https://github.com/Moskyera/hacash-wallet/commit/91f248d) — canonical v6/v7 meta resolution

## PQC Fullnode (Phases 1–3)

- [PR #2 — fullnodedev](https://github.com/Moskyera/fullnodedev/pull/2)
- Branch: [`feature/pqc-phases-1-3`](https://github.com/Moskyera/fullnodedev/tree/feature/pqc-phases-1-3)

## Integration / E2E Tests

- [hacash-wallet-integration](https://github.com/Moskyera/hacash-wallet-integration)

## Stack

| Repository | Role |
|------------|------|
| [hacash-wallet](https://github.com/Moskyera/hacash-wallet) | PQC/Hybrid accounts, Keystore v3, Type 4 send, desktop UI |
| [fullnodedev](https://github.com/Moskyera/fullnodedev) | PQC protocol APIs (Phases 1–3) |
| [hacash-wallet-integration](https://github.com/Moskyera/hacash-wallet-integration) | Audit gates & E2E smoke tests |

## Highlights

- Additive quantum fork of `hacash-wallet` v0.4 — legacy paths preserved
- Address version bytes (v6/v7) resolved from keystore + base58check decode — no prefix guessing
- CI green on wallet PR (Rust + desktop build)

---

*Open-source work toward Hacash quantum readiness.*