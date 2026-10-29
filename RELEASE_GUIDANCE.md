# Zenodo archiving: FALCON aggregated data v1.0.2

The GitHub release `v1.0.0` preceded enabling Zenodo. The `v1.0.1` release reached Zenodo but its archive was marked **Failed**. The former `.zenodo.json` included an unsupported relation `isRelatedTo` and lacked an explicit license; these have been corrected in the `main` branch on 29 October 2026. Zenodo's release error message should still be checked under the failed release → **Errors**; other failures are possible.

## Retry

1. Keep the dataset repository enabled (**ON**) in Zenodo → Account → GitHub.
2. Create a **new** GitHub release, tag `v1.0.2`, **target `main`**. Do not reuse or move earlier tags.
3. Title: **FALCON Yemen 2020 — Aggregated BGP Research Dataset v1.0.2**.
4. Release description: “Corrected Zenodo metadata for the curated aggregate BGP research dataset. This release contains aggregate BGP tables, event/reference comparisons, provenance records, and numerical consistency scripts. Original RIPE RIS/ioda publisher files and individual peer-prefix observations are excluded. Related research software: https://doi.org/10.5281/zenodo.23751733.”
5. No assets need attaching; GitHub/Zenodo archives the repository snapshot.
6. Confirm the GitHub release points to a commit **at or after `2492e4ffe1a050d5699e58c12669f788b2f4286b`**, containing updated `.zenodo.json`.
7. After publishing, in Zenodo open the release status. If **Failed**, click the release row, then **Errors**, and use the exact error to diagnose further.
8. If successful, confirm resource type **Dataset**, creator, **CC BY 4.0** for original aggregates/documentation, the actual files, and related software DOI. Capture the new version DOI.

Note: The root metadata assigns CC BY 4.0 to author-prepared aggregate data and original documentation only. It does not grant rights over external source data; the original code archive remains separately MIT licensed.

Dataset archival is not equivalent to full raw RIPE/ioda reprocessing.
