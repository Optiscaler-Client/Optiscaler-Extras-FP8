# Optiscaler-Extras-FP8

This repository hosts **automated mirrors** of the official AMD FSR4 (FP8) DLL, kept in sync with AMD's own SDK releases.

## ⚠️ Disclaimer
- **Not affiliated** with AMD or the official [OptiScaler project](https://github.com/optiscaler/OptiScaler).
- The DLL is extracted directly and unmodified from AMD's official [FidelityFX-SDK](https://github.com/GPUOpen-LibrariesAndSDKs/FidelityFX-SDK) releases — see each release's notes for the exact upstream SDK tag it was sourced from.
- All credit goes to AMD and the FidelityFX-SDK contributors.
- For the full SDK and its source, always visit the [official repository](https://github.com/GPUOpen-LibrariesAndSDKs/FidelityFX-SDK).

## Purpose
A [GitHub Actions workflow](.github/workflows/sync-fsr4-fp8.yml) periodically checks AMD's FidelityFX-SDK for new releases, extracts the FSR4 (FP8) upscaler/frame-generation DLL, and publishes it here as a lightweight `.7z` — useful for [Optiscaler-Client](https://github.com/Agustinm28/Optiscaler-Client) and other integrations that need direct access to official FP8 builds without downloading the full SDK.

## License
The FidelityFX SDK is licensed under **MIT** by AMD. This repository serves exclusively as a distribution mirror for the DLL asset.
