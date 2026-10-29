# Release guidance: aggregated data v1.0.0

1. On Zenodo → Account → GitHub, click **Sync now** if necessary and turn **ON** the integration for this distinct dataset repository.
2. In GitHub → Releases → Draft a new release, create the tag `v1.0.0` targeting `main`, after checking the archive file SHA-256.
3. Release title: **FALCON Yemen 2020 — Aggregated BGP Research Dataset v1.0.0**.
4. Description: “Author-prepared aggregate BGP measurements for January 2020, event/reference comparisons, summary arithmetic verification, and source URL/checksum provenance. Original third-party RIPE RIS and IODA files and individual peer/prefix records are not redistributed. The archive supports aggregate-level arithmetic reproducibility, not full raw-source reprocessing. Related MIT-licensed software: https://doi.org/10.5281/zenodo.23751733.”
5. **Before clicking Publish release:** review the intended data reuse license. Source package has none expressly assigned; Zenodo may assign its default CC BY 4.0 to public records. Choose and approve a specific license first, then set the same value in `.zenodo.json` before releasing if appropriate.
6. After Zenodo archives the release, inspect and, if necessary, edit the Zenodo resource type to **Dataset**, creator, license, access, related software DOI, and file list.
7. Cite the dataset version DOI (new one), **not** the pre-existing software version DOI.

GitHub Releases do not automatically become standalone DOI records until Zenodo is linked and actually archives the publication.
