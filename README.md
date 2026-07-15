# xcube-cci-registry

This repository contains generated and curated metadata artifacts for
`xcube-cci`:

- dataset registry artifacts;
- xcube `DataDescriptor` artifacts;
- xcube-cci state files;
- schemas for validating the artifacts;
- build provenance;
- human-readable build reports.

The metadata builder writes into this repository. Runtime packages such as
`xcube-cci` and `esa-climate-toolbox` should consume the published artifacts,
not the builder implementation.

## Layout

```text
registry.json
  Current registry artifact that maps canonical CCI dataset IDs to available
  store-specific representations. Published snapshots are represented by
  GitHub tags/releases. Reference-based representations such as Kerchunk may
  include their reference path directly in the representation metadata.

descriptors/
  Stored xcube DataDescriptor artifacts for the xcube-cci version named in
  build_info.json, grouped by store and data type.

states/
  Generated xcube-cci state files for the xcube-cci version named in
  build_info.json.

schemas/
  JSON Schemas for registry, states, and build info.

build_info.json
  Machine-readable provenance for the current generated artifacts, including
  the builder, xcube-cci, and xcube versions plus artifact counts.

reports/
  Human-readable reports for reviewing builder output.
```

## Principles

- The registry and state artifacts are data products, not Python package code.
- Registry releases are represented by GitHub tags/releases, not by release
  directories in this repository.
- Each registry release supports one `xcube-cci` version: the current published
  version recorded in `build_info.json`.
- Users who need an older `xcube-cci` version should use an older
  `xcube-cci-registry` release.
- State files must preserve manually curated fields such as `places`,
  `var_names`, and `pattern`.
- Build outputs should be reproducible and traceable through `build_info.json`.
- Reports are for review; machine-readable JSON artifacts are the primary
  integration surface.
