# Cosmoteer Mod Pack 2026

Version 1.0.6 is the current GitHub release. The files in this repository are not the mods.

`manifest.json` names pack `modpack-2026` and archive `modpack-2026-1.0.6.zip`. GitHub release files cannot exceed 2 GB, so that zip is uploaded as ordered parts:

- `modpack-2026-1.0.6.zip.000`
- `modpack-2026-1.0.6.zip.001`
- `modpack-2026-1.0.6.zip.002`

The mod pack launcher downloads the parts in that order and joins them back into the zip. Releases also attach `files-1.0.6.json` (per-file hashes) and, when useful, a `delta-…zip`. Launcher 1.0.3+ applies a matching delta when an older pack version is already cached, so upgrades do not re-download the full archive.

Version 1.0.6 caps Cable Age Remote Power at 512 tiles to avoid blueprint-overlay memory exhaustion on dense power nets. Contour Shields, Halo Remote Power, and ModPack Performance stay included. Stargate A.W.T is not included.

Newer versions are newer releases of this repository with their own `manifest.json`.
