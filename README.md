# Sovereign.OS — downloads

Public download mirror for [Sovereign.OS](https://sovereignos.pro). The application source lives in
a private repository; this repo only hosts installer releases.

Primary mirror (Cloudflare R2): `https://dl.sovereignos.pro/v<version>/<file>`

> [!CAUTION]
> **0.1.1 and 0.1.2 are deprecated.** Those packaged builds render broken (unstyled UI) due to a
> CSP nonce-injection bug in packaging. Download 0.1.3 or later.

## Latest — 0.1.3

| Platform | File |
|---|---|
| Windows (recommended) | [`Sovereign.OS_0.1.3_x64-setup.exe`](https://dl.sovereignos.pro/v0.1.3/Sovereign.OS_0.1.3_x64-setup.exe) — NSIS setup |
| Windows | [`Sovereign.OS_0.1.3_x64_en-US.msi`](https://dl.sovereignos.pro/v0.1.3/Sovereign.OS_0.1.3_x64_en-US.msi) |
| Linux (any distro) | [`Sovereign.OS_0.1.3_amd64.AppImage`](https://dl.sovereignos.pro/v0.1.3/Sovereign.OS_0.1.3_amd64.AppImage) |
| Debian / Ubuntu | [`Sovereign.OS_0.1.3_amd64.deb`](https://dl.sovereignos.pro/v0.1.3/Sovereign.OS_0.1.3_amd64.deb) |
| Fedora / RHEL | [`Sovereign.OS-0.1.3-1.x86_64.rpm`](https://dl.sovereignos.pro/v0.1.3/Sovereign.OS-0.1.3-1.x86_64.rpm) |

The same files are attached to the [releases](../../releases) here as a fallback.

Verify downloads with

```
sha256  0b036e3be3d3438c7ec6919933574ad5d70c6a2243988c458af4d699cac01bf4  Sovereign.OS_0.1.3_x64-setup.exe
sha256  07d0c52e72582c25733c7285bd65a3de2445ac3c63d098e42d70e40b04bc7193  Sovereign.OS_0.1.3_x64_en-US.msi
sha256  0e04c1007739eb5e8c86e4e98525a89b4db983fc17584a63d2c16d3bae3a7e45  Sovereign.OS_0.1.3_amd64.AppImage
sha256  6976ed95b483c420cd0a59d78b282bf85aefb5ee9069dd15bf78b9ec02a77b94  Sovereign.OS_0.1.3_amd64.deb
sha256  9ca127b6fbfc65f1860a9788d98a65b011d77d285da8cea150236e4e7330d5c0  Sovereign.OS-0.1.3-1.x86_64.rpm
```

Installers are unsigned — SmartScreen may warn on first run. The `.deb`/`.rpm` require
`libwebkit2gtk-4.1-0` and `libgtk-3-0`; the AppImage bundles them.

Questions: support@sovereignos.pro
