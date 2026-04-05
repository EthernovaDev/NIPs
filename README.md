# Nova Improvement Proposals (NIPs)

NIPs are the primary mechanism for proposing new features, standards, and protocol changes to the Ethernova network.

Anyone can submit a NIP. The process is designed to be open, transparent, and community-driven.

## What is a NIP?

A NIP is a design document providing information to the Ethernova community about a proposed change to the protocol, a new standard, or a process improvement. It should provide a concise technical specification of the feature and a rationale for why it should be adopted.

## NIP Types

| Type | Description |
|------|-------------|
| **Core** | Changes to the EVM, consensus rules, gas model, or anything that requires a hard fork |
| **Precompile** | New native precompile contracts (addresses 0x29+) |
| **Standard** | Application-level standards (token standards, wallet interfaces, etc.) |
| **Process** | Changes to the NIP process itself, governance, or development workflow |
| **Informational** | Design guidelines, general information, or ecosystem recommendations |

## NIP Statuses

```
Draft --> Review --> Accepted --> Final
                --> Rejected
                --> Withdrawn
```

- **Draft** — Initial proposal, open for feedback
- **Review** — Under active discussion by the community and core team
- **Accepted** — Approved for implementation
- **Final** — Implemented and deployed on mainnet
- **Rejected** — Not accepted (with rationale)
- **Withdrawn** — Withdrawn by the author

## How to Submit a NIP

1. Fork this repository
2. Copy `nip-template.md` to `NIPs/nip-XXXX.md` (use the next available number)
3. Fill in the template with your proposal
4. Submit a Pull Request
5. The community and core team will review and discuss

## Existing NIPs

| NIP | Title | Type | Status |
|-----|-------|------|--------|
| [NIP-0001](NIPs/nip-0001.md) | NIP Purpose and Guidelines | Process | Final |
| [NIP-0002](NIPs/nip-0002.md) | Noven Fork Specification | Core | Final |
| [NIP-0003](NIPs/nip-0003.md) | Native Chat Protocol | Standard | Draft |

## Resources

- [Ethernova Website](https://ethnova.net)
- [Ethernova GitHub](https://github.com/EthernovaDev/ethernova-coregeth)
- [Mainnet Explorer](https://explorer.ethnova.net)
- [Network Stats](https://ethnova.net/stats.html)
- [Telegram](https://t.me/EthernovaChain)
- [Discord](https://discord.gg/MYRzWpdcS2)

## Inspiration

This process is inspired by [Ethereum's EIPs](https://github.com/ethereum/EIPs), [Bitcoin's BIPs](https://github.com/bitcoin/bips), and [Solana's SIMDs](https://github.com/solana-foundation/solana-improvement-documents).
