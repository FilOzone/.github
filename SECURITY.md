# Security Policy

## Reporting a Vulnerability

If you discover a security vulnerability in any repository under the
[FilOzone](https://github.com/FilOzone) organization, please report it
responsibly. **Do not open a public issue.**

### For vulnerabilities in FOC smart contracts or services

Use GitHub's private vulnerability reporting feature, available in the
**Security** tab of the affected repository. This reaches the FOC
engineering team directly.

Repositories covered:
- [filecoin-services](https://github.com/FilOzone/filecoin-services) (FWSS, ServiceProviderRegistry)
- [pdp](https://github.com/FilOzone/pdp) (PDPVerifier)
- [filecoin-pay](https://github.com/FilOzone/filecoin-pay) (Filecoin Pay)
- [synapse-sdk](https://github.com/FilOzone/synapse-sdk) (Synapse SDK)
- [SessionKeyRegistry](https://github.com/FilOzone/SessionKeyRegistry)
- [dealbot](https://github.com/FilOzone/dealbot)

### For vulnerabilities in the Filecoin protocol

Bugs affecting the core Filecoin protocol (Lotus, builtin-actors, FVM,
F3, and other [in-scope repositories](https://immunefi.com/bug-bounty/filecoin/))
should be reported through the **Filecoin Bug Bounty Program** on
Immunefi:

> **https://immunefi.com/bug-bounty/filecoin/**

The program is administered by Filecoin Foundation and offers bounties
for qualifying vulnerabilities. A proof of concept is required for all
severity levels. See the
[Coordinated Disclosure Policy](https://fil.org/security/coordinated-disclosure-policy)
for details on the reporting process, timelines, and Safe Harbor
provisions.

### Bug bounty eligibility

The Immunefi bounty program covers the core Filecoin protocol
repositories listed on the
[program page](https://immunefi.com/bug-bounty/filecoin/). FOC
application-layer repositories (this organization) are **not currently
in the Immunefi scope**, but we take all reports seriously and will
coordinate with Filecoin Foundation where a vulnerability has
protocol-level implications.

## What to include in a report

- Description of the vulnerability and its potential impact
- Steps to reproduce or a proof of concept
- Affected version(s) or commit(s)
- Any suggested mitigation or fix

## What to expect

- Acknowledgement within 3 business days
- An initial assessment within 10 business days
- We will coordinate with you on disclosure timing

## Security contacts

For questions about this policy, reach out to the
[Filecoin Foundation security team](https://fil.org/security).
