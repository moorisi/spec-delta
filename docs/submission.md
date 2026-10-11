Category: **Builder → Intelligent Contracts**

Title: **SpecDelta: Consensus specification-obligation diff**

Notes / Description:

> SpecDelta compares two commit-pinned specification documents. Leader and validators independently fetch complete UTF-8 sources, verify both SHA-256 commitments, and extract bounded added and removed obligation sentences with source-anchored quotes. Validators repeat the comparison and require exact agreement on both source bytes and every consequential delta field; malformed, invented or unanchored obligations fail closed. The append-only history retains both commitments and the normalized change set for audit. This is a consensus diff primitive, not legal advice, compliance clearance or proof that an obligation was implemented. Repository authenticity and document completeness remain trust assumptions.

Evidence will be added after deployment verification.
