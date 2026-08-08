# Sovereign.OS — downloads

Public download mirror for [Sovereign.OS](https://sovereignos.pro). The application source lives in
a private repository; this repo only hosts installer releases.

Primary mirror (Cloudflare R2): `https://dl.sovereignos.pro/v<version>/<file>`

## Latest — 0.1.1

| Platform | File |
|---|---|
| Windows (recommended) | [`Sovereign.OS_0.1.1_x64-setup.exe`](https://dl.sovereignos.pro/v0.1.1/Sovereign.OS_0.1.1_x64-setup.exe) — NSIS setup |
| Windows | [`Sovereign.OS_0.1.1_x64_en-US.msi`](https://dl.sovereignos.pro/v0.1.1/Sovereign.OS_0.1.1_x64_en-US.msi) |
| Linux (any distro) | [`Sovereign.OS_0.1.1_amd64.AppImage`](https://dl.sovereignos.pro/v0.1.1/Sovereign.OS_0.1.1_amd64.AppImage) |
| Debian / Ubuntu | [`Sovereign.OS_0.1.1_amd64.deb`](https://dl.sovereignos.pro/v0.1.1/Sovereign.OS_0.1.1_amd64.deb) |
| Fedora / RHEL | [`Sovereign.OS-0.1.1-1.x86_64.rpm`](https://dl.sovereignos.pro/v0.1.1/Sovereign.OS-0.1.1-1.x86_64.rpm) |

The same files are attached to the [releases](../../releases) here as a fallback.

The Windows NSIS setup was rebuilt on 2026-08-08; verify with

```
sha256  0a87ad3682ee0b463c1d7987c905b7ca6107a142e17a251a7bda114ee274c07b  Sovereign.OS_0.1.1_x64-setup.exe
```

Installers are unsigned — SmartScreen may warn on first run. The `.deb`/`.rpm` require
`libwebkit2gtk-4.1-0` and `libgtk-3-0`; the AppImage bundles them.

Questions: support@sovereignos.pro
