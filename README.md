# VENGI

> The mission: Create a free, open-source and multi-platform voxel editor and command line tools with animation support to support artists and developers.

**Category:** VOXELIZATION · **Ecosystem:** unknown · **Vendored upstream:** https://github.com/vengi-voxel/vengi · **Pinned commit:** `c7d5b7cd7fe48baa4b29258ef5f92af59da95325` · **Vendor:** Anticloud FZ LLE

## What This Project Is

The mission: Create a free, open-source and multi-platform voxel editor and command line tools with animation support to support artists and developers.

This is the upstream project, vendored at the pinned commit above and packaged offline-first. The 12 improvements Anticloud adds live in `anticloud/` and are described under *Anticloud Overlay* below. Every fact in this file traces to a file in this directory.

## Installation

```
# See the upstream README (linked above) for build steps.
```

## Usage

See the upstream README (linked above) for usage. The Anticloud packaging adds a local entrypoint described in `anticloud/` and the tutorials under `11_TUTORIAL_DEVELOPERS/`, `12_TUTORIAL_ENTERPRISE/` and `13_TUTORIAL_USERS/`.

## Anticloud Overlay

The 12 improvements live under `anticloud/`. Run the check suite from this directory:

```
python anticloud/bench/runner.py --cwd anticloud
```

## Benchmark Results

The suite is recorded in `BENCH.json`; no benchmark rows were found in this package.

## Licence

The upstream licence is preserved in `LICENSE` and `THIRD_PARTY_LICENSES/`. The Anticloud overlay is licensed under Anticommons 0.1.0 (`ANTICOMMONS_LICENSE.md`).

## Verification

SHA3-256 of `BENCH.json`:

```
4bcc41e61c0ea3336c99aa70b15fda8edfbac8e3ca7a812198502ca2f9fc2c9d
```

Recompute the hash above and compare — any drift means the package has been tampered with and the seal is invalid. This is a self-assessment; no external audit has been performed and a SOC 2 / NIST independent audit is committed post-funding.
