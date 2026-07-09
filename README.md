# Mosky — Hacash · Wallet · Miner

Post-quantum & mining tooling for the **Hacash** ecosystem.

## ⭐ Popular repositories

| | Repository | Description |
|---|------------|-------------|
| 🖥️ | **[fullnodedev](https://github.com/Moskyera/fullnodedev)** | **HAC Miner Panel** — GUI, OpenCL miners (AMD/NVIDIA), solo mining · [**Releases ↗**](https://github.com/Moskyera/fullnodedev/releases) |
| 💎 | **[hacash-wallet](https://github.com/Moskyera/hacash-wallet)** | Secure Hacash desktop wallet (encrypted vault, L1 send) |
| 🦀 | **[rust](https://github.com/Moskyera/rust)** | Rust Hacash node & SDK |

### Miner downloads (Windows)

| Package | When to use |
|---------|-------------|
| [**Full**](https://github.com/Moskyera/fullnodedev/releases) `hacash-miner-full-*` | Clean PC — fullnode + miners + panel |
| [**Miner only**](https://github.com/Moskyera/fullnodedev/releases) `hacash-miner-only-*` | You already run `hacash.exe` |

Extract → `SETUP.bat` or `SETUP-MINER.bat` → `miner-panel.exe`

---

## HAC Miner Panel · By Mosky

- **miner-panel.exe** — settings, dashboard, auto-tune GPU, 9 languages
- **poworker** / **diaworker** — HAC blocks & HACD diamonds (OpenCL)
- [docs/MINING-AMD.md](https://github.com/Moskyera/fullnodedev/blob/main/docs/MINING-AMD.md)

## Quantum Wallet v0.4

- **ML-DSA-65** · **v6 PQC** / **v7 Hybrid** · **Keystore v3** · **Type 4** on-chain transfers
- [hacash-wallet](https://github.com/Moskyera/hacash-wallet) · [PR #1](https://github.com/Moskyera/hacash-wallet/pull/1)
- Branch: [`feature/quantum-react-v0.4`](https://github.com/Moskyera/hacash-wallet/tree/feature/quantum-react-v0.4)

## PQC Fullnode (Phases 1–3)

- [fullnodedev](https://github.com/Moskyera/fullnodedev) · [PR #2](https://github.com/Moskyera/fullnodedev/pull/2)

## Integration / E2E Tests

- [hacash-wallet-integration](https://github.com/Moskyera/hacash-wallet-integration)

## Stack

| Repository | Role |
|------------|------|
| [fullnodedev](https://github.com/Moskyera/fullnodedev) | Miner panel, OpenCL workers, PQC fullnode dev |
| [hacash-wallet](https://github.com/Moskyera/hacash-wallet) | PQC/Hybrid accounts, Keystore v3, desktop UI |
| [rust](https://github.com/Moskyera/rust) | Hacash node & SDK |
| [hacash-wallet-integration](https://github.com/Moskyera/hacash-wallet-integration) | Audit gates & E2E smoke tests |

---

*Open-source Hacash tools — mining, wallet, quantum readiness.*