# S1 — When Revocation Does Not End Access

*Temporal Repair Dependencies in Application Compromise*  
**Zawwar Sami** · S Series · **Independent preprint, Version 1** · 17 October 2026 · 17 pages

What happens when the old credentials stop working, but the application can still create new ones? I examine this through a renewal-graph argument and a running HTTP testbed. Across 48 distinct repair-and-renewal schedules, 20 retain access even though every original credential is rejected. A delayed-work example compares cancellation and an issuance-epoch check, with a positive control for reopening the service.

Equifax, Exchange and MOVEit motivate the application, identity and restoration boundaries. The experiments are controlled local demonstrations; they do not establish that the constructed repair sequences occurred in those incidents.

## Read and reproduce

- [**Read the complete 17-page PDF**](Zawwar-Sami-S1-Temporal-Repair-Dependencies-v1.pdf)
- [Public reproducibility archive: six Python modules, raw results and walkthrough](S1-v1-reproducibility.zip)
- [Official paper page](https://zawwarsami.com/writing/when-revocation-does-not-end-access)
- [PDF on the official website](https://zawwarsami.com/papers/Zawwar-Sami-S1-Temporal-Repair-Dependencies-v1.pdf)
- [Long-Term Vision — S Series Book I](https://zawwarsami.com/research#S)
- [Zenodo archive](https://zenodo.org/records/23435843)
- [DOI: 10.5281/zenodo.23435843](https://doi.org/10.5281/zenodo.23435843)
- [PhilPapers](https://philpapers.org/rec/SAMWRD)
- [ORCID](https://orcid.org/0009-0004-5819-3017)

This is the exact PDF deposited on Zenodo. SHA-256: `428f59e657e8c1c43176e14a07052db9a67d1f355e1b099258a2d3b39570a1f3`. It is an independent research preprint. The accompanying code uses synthetic credentials and canaries, with no private incident logs.

## Discuss and test

**[Join the focused S1 Q&A — discussion #22](https://github.com/Zawwarsami16/Public-Research-Tree/discussions/22)**

What is the smallest additional observation that would distinguish a successful revocation from durable loss of access in a real service?

[Detailed evidence, corrections and replication — issue #21](https://github.com/Zawwarsami16/Public-Research-Tree/issues/21). Counterexamples to the stated premises, earlier work and reproducible comparisons are welcome.

[← Security & Adversarial Systems](../) · [All research worlds](../../)
