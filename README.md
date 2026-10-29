# FALCON Yemen 2020 — Aggregated BGP Research Dataset

This repository contains a curated **aggregate-data archive** for the study *Network-Specific BGP Route Reconfiguration During Yemen's January 2020 FALCON Disruption: A Multi-Collector Measurement Study*.

**Researcher:** Ezzaldeen Al-Tayar — Faculty of Engineering and Information Technology, Taiz University, Yemen.

## Download the verified dataset

- [FALCON aggregated data v1.0.0 (.tar.xz)](FALCON_Yemen_2020_Aggregated_BGP_Dataset_v1.0.0.tar.xz) — 12 text/CSV/JSON/Python files in one archive.
- SHA-256 of the archive: `9b5755d022faf02a02e2d77237d9526d24dc336e8f67d5708048c054db1aa254`.
- Extraction: `tar -xJf FALCON_Yemen_2020_Aggregated_BGP_Dataset_v1.0.0.tar.xz`.
- Verification after extraction: `python verify_aggregate_tables.py` (Python 3.10+); `FILES_SHA256.json` lists hashes of included files.

The .tar.xz archive above is the dataset source of record for the GitHub release.

## Contents and research limits

This package includes high-level collector×ASN×window BGP tables, six event/reference contrasts, fixed-cohort sensitivity summaries, AS12486 IPv6 endpoint-retention summaries, a deterministic aggregate-arithmetic validator, RIPE RIS source URLs and reported SHA-256 hashes, and IODA publisher-image source links.

It **does not** include original RIPE RIS MRT files, individual peer-prefix BGP observations, IODA originals/pixel traces/2023 JSON, internal reviews or unpublished manuscript files. Verification tests the reported summary arithmetic; it is **not** independent reprocessing of original RIPE MRT files and does not establish physical submarine-cable causality or end-user outage.

The repository owner expressly authorized public distribution of these author-prepared aggregates on 29 October 2026, as distinct from rights to redistribute excluded provider-origin materials. **No public reuse license for these aggregate data has yet been selected in the source package.** Public GitHub visibility is not itself a license. Zenodo's license selection must be reviewed before publication.

## Related research software

[Curated FALCON research software v1.0.1](https://doi.org/10.5281/zenodo.23751733) (MIT-licensed author-owned source code only). This dataset is a separate deposit and should receive its own DOI after Zenodo archives a release from this repository.

See also [RELEASE_GUIDANCE.md](RELEASE_GUIDANCE.md).
