# LIT — Verifiable Content Review Protocol

LIT is a protocol for cryptographically verifiable content review.
It binds a specific piece of content to a review process, a policy version,
and a point in time, without relying on reputation systems or social scoring.

## What LIT is
- A specification for creating and verifying review attestations ("stamps")
- Content-addressed: edits invalidate prior verification
- Time-bound: verification reflects conditions at issuance time
- Policy-explicit: the applied rules are named and versioned
- Client-verifiable: anyone can independently verify an attestation

## What LIT is not
- A truth oracle
- A reputation or karma system
- A social network or platform
- A fact-checking authority
- A guarantee of permanent correctness

## Core idea
If content has been reviewed under explicit rules at a specific time,
that fact should be provable, portable, and inspectable.
Copies, edits, or forks that diverge from the reviewed content
should lose verification automatically.

## Status
This is an early draft (v0.1). The protocol is intentionally minimal.
Breaking changes may occur.
