# OmniCalc downloads

Installers for **OmniCalc** by [MJS Applications](https://mjsapps.net) — one calculator for
every subject. This repository holds downloads only; the source code is not here.

**Get the newest version:** <https://github.com/msanty573/OmniCalc-Downloads/releases/tag/latest>

| Computer | File |
|---|---|
| Mac (Apple silicon) | [OmniCalc-macOS-arm64.dmg](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/OmniCalc-macOS-arm64.dmg) |
| Windows on ARM — installer | [OmniCalc-Setup-arm64.exe](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/OmniCalc-Setup-arm64.exe) |
| Windows on ARM — portable zip | [OmniCalc-windows-arm64-portable.zip](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/OmniCalc-windows-arm64-portable.zip) |
| Linux x86-64 — tar.gz | [OmniCalc-linux-x86_64.tar.gz](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/OmniCalc-linux-x86_64.tar.gz) |
| Linux x86-64 — RPM (RHEL/Fedora) | [omnicalc.el10.x86_64.rpm](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/omnicalc.el10.x86_64.rpm) |

The release notes list which version each file is.

## First launch

OmniCalc isn't signed with a paid Apple or Microsoft developer certificate yet, so the
first launch shows a warning:

- **Mac:** open the .dmg and drag OmniCalc to Applications. The first time you open it,
  macOS says it can't verify the app — click **Done**, then go to **System Settings →
  Privacy & Security**, scroll down and click **Open Anyway**.
- **Windows:** if SmartScreen says "Windows protected your PC", click **More info →
  Run anyway**.
- **Linux:** extract the tar.gz and run `./install.sh`, or `sudo dnf install ./omnicalc.el10.x86_64.rpm`.
