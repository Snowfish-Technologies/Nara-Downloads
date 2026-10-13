# Nara Downloads

Last updated: 2026-10-13

Official Windows installers for Nara by Snowfish Technologies. This repository
holds release assets only; it contains no source code.

Each release has:

- `Nara-Setup-win-x64.exe` (signed)
- `Nara-Setup-win-arm64.exe` (signed)
- `SHA256SUMS.txt`

Before you run an installer, check its checksum:

```powershell
Get-FileHash .\Nara-Setup-win-x64.exe -Algorithm SHA256
```

The hash must match the line in `SHA256SUMS.txt` for that file. The primary
download location is https://download.donebynara.com/; this repository is an
independent backup of the same signed files.

## Changelog

- 2026-10-13: Created the backup download repository (Devin, for Ben).
