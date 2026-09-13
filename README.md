<p align="center"><img src="thumbnail.png" width="220"></p>

<h1 align="center">Sephora Sniper v3.0</h1>
<p align="center">Made with love by rickyita</p>
<p align="center">
  <a href="https://github.com/astralisdev/Sephora-sniper-releases/releases/latest"><img src="https://img.shields.io/github/downloads/astralisdev/Sephora-sniper-releases/total?label=downloads&color=2ecc71" alt="downloads"></a>
  <img src="https://hits.sh/github.com/astralisdev/Sephora-sniper-releases.svg?label=visits&color=ff2d55" alt="visits">
</p>

Discord alerts the moment your product is back in stock online or at your Sephora stores.

## Download

| Computer | File |
|---|---|
| Mac with Apple chip (M1/M2/M3/M4) | [SephoraSniper-mac-apple-silicon](https://github.com/astralisdev/Sephora-sniper-releases/releases/latest/download/SephoraSniper-mac-apple-silicon) |
| Mac with Intel chip | [SephoraSniper-mac-intel](https://github.com/astralisdev/Sephora-sniper-releases/releases/latest/download/SephoraSniper-mac-intel) |
| Windows | [SephoraSniper-windows.exe](https://github.com/astralisdev/Sephora-sniper-releases/releases/latest/download/SephoraSniper-windows.exe) |
| Everything in one folder | [Sephora.Sniper.v3.0.zip](https://github.com/astralisdev/Sephora-sniper-releases/releases/latest/download/Sephora.Sniper.v3.0.zip) |

Not sure which Mac you have? Apple menu → About This Mac → "Chip" or "Processor".

Put the file in its own folder: your settings are saved next to it.

## First launch

**Mac**
1. Double-click the file. macOS blocks it ("cannot be verified").
2. Open System Settings → Privacy & Security, scroll down, click **Open Anyway**, confirm.
3. If it still won't open, run this in Terminal from the file's folder:
   ```
   xattr -d com.apple.quarantine SephoraSniper-mac-*
   chmod +x SephoraSniper-mac-*
   ```

**Windows**
Double-click `SephoraSniper-windows.exe`. If "Windows protected your PC" shows up, click **More info → Run anyway**. Use Windows Terminal so the emojis display.

## Setup

| Menu | What to do |
|---|---|
| 5 | Paste your Discord webhook, send a test alert |
| 8 | Choose your country |
| 2 | Add the stores to watch (`c` looks them up by city) |
| 4 | Turn online / in-store alerts on or off |
| 1 | Start the monitor (Ctrl-C stops it) |
