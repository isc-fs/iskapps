# iskApps — ISC FS Racing Team app releases

Public download + auto-update channel for the team's desktop apps. Each app's
source lives in its own (often private) repository; this repo only hosts the
released installers so the apps' built-in update checks can reach them.

## Release naming

Each app tags its releases with an app prefix so multiple apps can share this
repo without clashing:

```
<app>-vX.Y.Z      e.g.  wario-charger-v1.3.0
```

An app's update check lists this repo's releases and picks the newest one
matching **its own** prefix.

## Apps

| App | Tag prefix | What it is |
|-----|-----------|------------|
| **ISC Wario Charger** | `wario-charger-v` | AMS pit display & charge controller (IFS08) |
| **ISC MingoCAN** | `mingocan-v` | Flash, monitor & debug CAN on the team's STM32 ECUs (IFS08) |

## Download

Open [**Releases**](../../releases), find your app's latest `<app>-v…` tag, and
grab the installer for your platform (`.dmg` / `.exe` / `.deb` / `.rpm` / `.AppImage`).
