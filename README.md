# ZeroSeal Official Releases

Official compiled Windows binary releases and SHA-256 verification checksums for **ZeroSeal** offline security utilities (**Pass-in**, **Lock-in**, and future tools).

> **Closed-Source Binary Distribution:** This repository contains **only** compiled release archives and `SHA256SUMS.txt`. Source code is never hosted here.

## Links
- **Official Website & SHA-256 Verifier:** https://zeroseal.pages.dev
- **Download Center:** https://zeroseal.pages.dev/downloads
- **Security Architecture:** https://zeroseal.pages.dev/security
- **Private Vulnerability Reporting:** https://github.com/zeroseal-app/zeroseal-releases/security/advisories/new

## Verify Your Download (PowerShell)
```powershell
Get-FileHash .\PassIn-v2.0-win-x64.zip -Algorithm SHA256
```
Compare the output against `SHA256SUMS.txt` attached to the release and listed on https://zeroseal.pages.dev/downloads#verify.
