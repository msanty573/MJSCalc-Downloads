# MJSCalc downloads

Installers for **MJSCalc** by [MJS Applications](https://mjsapps.net) — one calculator for
every subject. This repository holds downloads only; the source code is not here.

**Easiest:** <https://mjsapps.net/mjscalc/> recommends the right file for your computer.
Not sure yet? [Try it in your browser first](https://mjsapps.net/mjscalc/try/).

**All files:** <https://github.com/msanty573/OmniCalc-Downloads/releases/tag/latest> (the
release notes list which version each file is).

| Computer | File |
|---|---|
| Mac with Apple silicon (M1 or newer) | [MJSCalc-macOS-arm64.dmg](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/MJSCalc-macOS-arm64.dmg) |
| Mac with an Intel processor | [MJSCalc-macOS-x86_64.dmg](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/MJSCalc-macOS-x86_64.dmg) |
| Windows (Intel or AMD) — installer | [MJSCalc-Setup-x64.exe](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/MJSCalc-Setup-x64.exe) |
| Windows (Intel or AMD) — portable zip | [MJSCalc-windows-x64-portable.zip](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/MJSCalc-windows-x64-portable.zip) |
| Windows on ARM — installer | [MJSCalc-Setup-arm64.exe](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/MJSCalc-Setup-arm64.exe) |
| Windows on ARM — portable zip | [MJSCalc-windows-arm64-portable.zip](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/MJSCalc-windows-arm64-portable.zip) |
| Linux (Intel or AMD) — tar.gz | [MJSCalc-linux-x86_64.tar.gz](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/MJSCalc-linux-x86_64.tar.gz) |
| Linux (Intel or AMD) — RPM (RHEL, AlmaLinux, Rocky, Fedora) | [mjscalc.el10.x86_64.rpm](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/mjscalc.el10.x86_64.rpm) |
| Linux (Intel or AMD) — .deb (Ubuntu 26.04+) | [mjscalc.ubuntu.amd64.deb](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/mjscalc.ubuntu.amd64.deb) |
| Linux on ARM — tar.gz | [MJSCalc-linux-aarch64.tar.gz](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/MJSCalc-linux-aarch64.tar.gz) |
| Linux on ARM — RPM | [mjscalc.el10.aarch64.rpm](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/mjscalc.el10.aarch64.rpm) |
| Linux on ARM — .deb (Ubuntu 26.04+) | [mjscalc.ubuntu.arm64.deb](https://github.com/msanty573/OmniCalc-Downloads/releases/download/latest/mjscalc.ubuntu.arm64.deb) |

**System requirements:** macOS 12 Monterey or newer · 64-bit Windows 10 or 11 (Windows 11
on ARM PCs) · 64-bit Linux. MJSCalc uses about 250–350 MB of memory and 130–220 MB of disk
space.

## First launch

MJSCalc isn't signed with a paid Apple or Microsoft developer certificate yet, so the
first launch shows a warning:

- **Mac:** open the .dmg and drag MJSCalc to Applications. The first time you open it,
  macOS says it can't verify the app — click **Done**, then go to **System Settings →
  Privacy & Security**, scroll down and click **Open Anyway**. (On macOS 12–14 you can
  also Control-click MJSCalc, choose **Open**, then **Open** again.)
- **Windows:** if SmartScreen says "Windows protected your PC", click **More info →
  Run anyway**.
- **Linux:** install the .deb (`sudo apt install ./mjscalc.ubuntu.*.deb`, which also sets
  up updates through apt) or the RPM (`sudo dnf install ./mjscalc.el10.*.rpm`), or extract
  the tar.gz and run `./install.sh`. To get RPM updates through dnf, add the repository once:

  ```
  sudo rpm --import https://msanty573.github.io/OmniCalc-Downloads/RPM-GPG-KEY-omnicalc
  sudo curl -o /etc/yum.repos.d/omnicalc.repo https://msanty573.github.io/OmniCalc-Downloads/omnicalc.repo
  ```

## Updates

**Help → Check for Updates…** finds and installs new versions; the .deb (and the RPM, once
its repository is added) also updates with your system's other updates.

## Security

Found a security problem? Please report it privately — see [SECURITY.md](SECURITY.md).
