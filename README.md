# PGGB downloads

**Current version: PGGB 9.1.04**

Each link below downloads the newest version. Earlier versions are on the [Past releases](PAST-RELEASES.md) page.

## PGGB app

### Windows

- Installer: [PGGB-Windows-Setup.exe](https://github.com/remastero/pggb-downloads/releases/latest/download/PGGB-Windows-Setup.exe)

### Mac

- Apple Silicon: [PGGB-Mac-Apple-Silicon.pkg](https://github.com/remastero/pggb-downloads/releases/latest/download/PGGB-Mac-Apple-Silicon.pkg)
- Intel: [PGGB-Mac-Intel.pkg](https://github.com/remastero/pggb-downloads/releases/latest/download/PGGB-Mac-Intel.pkg) (please read the note below first)

> **Before you download for Intel Mac**
>
> Live and Offline processing are slower on Intel Macs than on Apple Silicon. Try PGGB on your computer first to see whether it meets your needs.
>
> Live outputs PCM only. DSD files can still play in Bypass or be converted to PCM. Offline can still create DSD files.
>
> If you have an Apple Silicon Mac, choose the Apple Silicon installer. The Intel version runs through Rosetta and keeps the same performance and Live output limitations.
>
> Try PGGB free for 30 days, with no credit card needed. Free Lite remains available afterwards.

Not sure which Mac you have? Open the Apple menu and choose About This Mac. "Chip: Apple M1" (or M2, M3 and so on) means Apple Silicon; "Processor: ... Intel" means Intel.

## PGGB-Audio-Link (PAL) endpoint

Install the endpoint on the computer connected to your DAC. Choose its operating system and processor below.

### Windows

- Installer: [PGGB-Audio-Link-Windows-Setup.exe](https://github.com/remastero/pggb-downloads/releases/latest/download/PGGB-Audio-Link-Windows-Setup.exe)
- Portable command-line endpoint: [PGGB-Audio-Link-Windows-Portable.exe](https://github.com/remastero/pggb-downloads/releases/latest/download/PGGB-Audio-Link-Windows-Portable.exe)

### Mac

- Apple Silicon and Intel (.pkg): [PGGB-Audio-Link-Mac.pkg](https://github.com/remastero/pggb-downloads/releases/latest/download/PGGB-Audio-Link-Mac.pkg)

### Debian, Ubuntu and Raspberry Pi OS

- Intel / AMD 64-bit (.deb): [pggb-audio-link_amd64.deb](https://github.com/remastero/pggb-downloads/releases/latest/download/pggb-audio-link_amd64.deb)
- ARM64 (.deb): [pggb-audio-link_arm64.deb](https://github.com/remastero/pggb-downloads/releases/latest/download/pggb-audio-link_arm64.deb)

### Fedora and other RPM systems

- Intel / AMD 64-bit (.rpm): [pggb-audio-link.x86_64.rpm](https://github.com/remastero/pggb-downloads/releases/latest/download/pggb-audio-link.x86_64.rpm)
- ARM64 (.rpm): [pggb-audio-link.aarch64.rpm](https://github.com/remastero/pggb-downloads/releases/latest/download/pggb-audio-link.aarch64.rpm)

### Arch Linux

- Intel / AMD 64-bit (.pkg.tar.zst): [pggb-audio-link-x86_64.pkg.tar.zst](https://github.com/remastero/pggb-downloads/releases/latest/download/pggb-audio-link-x86_64.pkg.tar.zst)
- ARM64 (.pkg.tar.zst): [pggb-audio-link-aarch64.pkg.tar.zst](https://github.com/remastero/pggb-downloads/releases/latest/download/pggb-audio-link-aarch64.pkg.tar.zst)

## Other downloads

### Mac disk images (.dmg)

The same Mac app as a disk image: drag the apps into Applications, then install the optional PGGB Bridge driver by hand from the disk image. The .pkg installers above do all of this in one guided install.

- Apple Silicon: [PGGB-Mac-Apple-Silicon.dmg](https://github.com/remastero/pggb-downloads/releases/latest/download/PGGB-Mac-Apple-Silicon.dmg)
- Intel: [PGGB-Mac-Intel.dmg](https://github.com/remastero/pggb-downloads/releases/latest/download/PGGB-Mac-Intel.dmg) (the Intel Mac note above applies)

## About the "Source code" files

GitHub adds "Source code (zip)" and "Source code (tar.gz)" to every release by itself, and a "Code" button to this page; they cannot be removed. They hold only the text of these pages, not PGGB. Please use the files listed above.

**Open-source components**: PGGB uses five libraries under the LGPL 2.1. Their exact sources, our changes and the license are in [PGGB 9.1.05 open-source sources](https://github.com/remastero/pggb-downloads/releases/tag/sources-9.1.05).
