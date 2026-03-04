<h1 align="center">FilOzone</h1>
<p align="center">
  Building Filecoin Onchain Cloud (FOC) infrastructure for building production-ready Filecoin applications.
</p>

<p align="center">
  <a href="https://github.com/FilOzone/synapse-sdk">Synapse SDK</a> •
  <a href="https://github.com/FilOzone/filecoin-services">Filecoin Services</a> •
  <a href="https://github.com/FilOzone/filecoin-pay">Filecoin Pay</a> •
  <a href="https://github.com/FilOzone/pdp">PDP</a> •
  <a href="#featured-live-demos">Live Demos</a> •
  <a href="https://docs.filecoin.cloud/">Docs</a>
</p>

---

## Build with FOC

Filecoin Onchain Cloud (FOC) is a programmable, verifiable cloud on Filecoin where storage, retrieval, and payments run via smart contracts.

- [About FOC](https://docs.filecoin.cloud/introduction/about/)
- [Why FOC](https://docs.filecoin.cloud/introduction/why/)
- [FOC Architecture](https://docs.filecoin.cloud/core-concepts/architecture/)
- [Get Started with Synapse SDK](https://docs.filecoin.cloud/getting-started/)

## Featured Live Demos

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://pin.filecoin.cloud">
        <img src="./pin-filecoin-cloud.png" alt="Screenshot of pin.filecoin.cloud demo" />
      </a>
      <h3>Filecoin Pin</h3>
      <p>
        Decentralized IPFS pinning backed by Filecoin storage providers and onchain proofs.
        Use this demo to upload content, pin it, and understand the persistence model for production apps.
      </p>
      <p>
        <a href="https://pin.filecoin.cloud">Open Demo</a> •
        <a href="https://github.com/filecoin-project/filecoin-pin">GitHub</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <a href="https://foc-demo.filbuilders.eth.limo">
        <img src="./foc-upload-dapp-demo.png" alt="Screenshot of foc-upload-dapp demo" />
      </a>
      <h3>FOC Upload dApp</h3>
      <p>
        End-to-end starter dApp for upload and storage workflows with wallet auth, dataset management,
        and payment flows. Use it as a practical template for builder integrations on Filecoin Onchain Cloud.
      </p>
      <p>
        <a href="https://foc-demo.filbuilders.eth.limo">Open Demo</a> •
        <a href="https://github.com/FIL-Builders/foc-upload-dapp">GitHub</a>
      </p>
    </td>
  </tr>
</table>

### Which Demo Should I Start With?

- Start with **Filecoin Pin** if you want IPFS-style pinning plus verifiable Filecoin persistence.
- Start with **FOC Upload dApp** if you want a full application scaffold for uploads, balances, and storage UX.

## Core Stack

| Project | What it is | Best for |
|---|---|---|
| [synapse-sdk](https://github.com/FilOzone/synapse-sdk) | JavaScript SDK for FOC integrations | App developers building quickly |
| [filecoin-services](https://github.com/FilOzone/filecoin-services) | Service and API layer for core workflows | Backend and platform teams |
| [filecoin-pay](https://github.com/FilOzone/filecoin-pay) | Payment and settlement primitives | Monetization and billing flows |
| [pdp](https://github.com/FilOzone/pdp) | Proof of Data Possession contracts and utilities | Verifiable storage workflows |

## Start Here

- New to FOC: start with [Get Started](https://docs.filecoin.cloud/getting-started/) and then [synapse-sdk](https://github.com/FilOzone/synapse-sdk)
- Running a Filecoin devnet with the core FOC contract in place: [foc-devnet](https://github.com/FilOzone/foc-devnet)
- Check out FOC related explorers:
  - [pdp-explorer](https://github.com/FilOzone/pdp-explorer)
  - [filecoin-pay-explorer](https://github.com/FilOzone/filecoin-pay-explorer)

## Contributing

Issues and PRs are welcome across all repositories. For feature requests, open an issue in the closest matching repo and include your use case.
