# AalxlolCode releases

Public channel for AalxlolCode installers and the signed license revocation
list. This repository does not contain source code.

- **Installers:** download the latest build from [Releases](../../releases/latest).
- **Revocations:** the `revocations` branch holds `revocations.json`, the signed
  list consumed by installed apps.
- **Updates:** the desktop app reads `latest.yml` from this repository and
  installs updates automatically.

The current Windows installer is not code-signed yet, so SmartScreen may show a
warning on first launch.
