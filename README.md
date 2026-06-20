# Spyridon Gagrinas

Founder @ **QUBEX Sentinel** — building post-quantum cryptography
infrastructure for institutional crypto custody.

## What I'm Building
Institutional crypto sits on ECDSA-secured chains. Those public keys are
exposed to "harvest now, decrypt later": data captured today can be
broken once a cryptographically relevant quantum computer exists
(most estimates put that in the 2030s, with real uncertainty).

**QUBEX Sentinel** is a NIST-standard ML-DSA-87 verification checkpoint
that institutions can add inside their own internal authorization flow —
independently checkable, no chain migration, no custody of keys or
funds.

Honest limit: this doesn't protect an already-exposed public key from
an attacker broadcasting directly to the chain — only the chain itself
can close that, through migration or opt-in account abstraction (e.g.
Ethereum's EIP-8141 direction). What it adds is a verification
checkpoint inside an institution's own process, and demonstrable
readiness for what comes next.

## Current Status

- **Live:** ML-DSA-87 (FIPS 204, level 5) benchmark + stateless
  verification API returning signed, independently-verifiable
  attestations, with a persistent attestation identity.
- **In progress:** institutional integration path.
- **Research:** ZK proof that verification ran correctly.

Direction (not date-promises): verification API → independent security
review → institutional pilots.

## Key Projects

- [Qubex-PQC-Benchmarks](https://github.com/SpirosDR1/Qubex-PQC-Benchmarks)
  — ML-DSA-87 benchmark + verification API with signed attestations.

## Connect

- **Site:** https://qubexsentinel.com
- **X:** [@QUBEX_SENTINEL](https://x.com/QUBEX_SENTINEL) | [@Spiros_Gagrinas](https://x.com/Spiros_Gagrinas)
- **Discord:** https://discord.gg/ZQXZcNVcR
- **LinkedIn:** [Spyridon Gagrinas](https://www.linkedin.com/in/spyridon-g-9858b03a0/)
- **Farcaster:** [QUBEX Sentinel](https://farcaster.xyz/qubexsentinel)
- **Email:** spyridongagr@qubexsentinel.com

---

Building the verification layer institutional crypto needs for the
quantum transition.
*No fluff. No fake metrics. Just execution.*
