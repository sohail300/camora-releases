<p align="center">
  <a href="https://www.getcamora.in">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://www.getcamora.in/assets/camora/camora-logo-white.svg">
      <img src="https://www.getcamora.in/assets/camora/camora-logo.svg" alt="Camora" width="260">
    </picture>
  </a>
</p>

<h3 align="center">Use your Android phone as a webcam on Windows 11 and Ubuntu</h3>

<p align="center">
  Free · No account · USB or Wi-Fi · Works in Zoom, Google Meet, Microsoft Teams and OBS
</p>

<p align="center">
  <a href="https://www.getcamora.in/download"><b>Download</b></a> ·
  <a href="https://www.getcamora.in/guide">Setup guide</a> ·
  <a href="https://github.com/sohail300/camora-releases/releases/latest">Latest release</a>
</p>

<p align="center">
  <img src="https://www.getcamora.in/assets/camora/desktop-live-v3.webp" alt="Camora on a computer showing the phone's camera, live" width="640">
</p>

---

**Camora** turns your Android phone into a webcam for your computer. Your phone's camera is far better than most laptop webcams; Camora sends its picture to your computer, where it shows up as a normal camera called **“Camora”** in every video app.

This repository holds Camora's **releases** (the app downloads). The website, with the full setup guide, is **[getcamora.in](https://www.getcamora.in)**.

## Download

| | File | For |
|---|---|---|
| 📱 | [`Camora-Android.apk`](https://github.com/sohail300/camora-releases/releases/latest/download/Camora-Android.apk) | The phone app. Android 8.0 or newer. |
| 🪟 | [`Camora-Windows-setup.exe`](https://github.com/sohail300/camora-releases/releases/latest/download/Camora-Windows-setup.exe) | Windows 11, 64-bit |
| 🐧 | [`Camora-Ubuntu-24.04.deb`](https://github.com/sohail300/camora-releases/releases/latest/download/Camora-Ubuntu-24.04.deb) | Ubuntu 24.04, 64-bit |
| 🐧 | [`Camora-Ubuntu-26.04.deb`](https://github.com/sohail300/camora-releases/releases/latest/download/Camora-Ubuntu-26.04.deb) | Ubuntu 26.04, 64-bit |

You need both: the app on your phone, and the app on your computer. Each release also has a `SHA256SUMS.txt` to check your download.

## What it does

- **Your phone as a webcam:** front or back camera, 720p or 1080p, and 60 fps if your phone supports it.
- **USB or Wi-Fi:** USB has the lowest delay (about 150 ms from camera to screen on Windows) and charges the phone; over Wi-Fi you pair once with a 6-digit code and it reconnects by itself.
- **Works everywhere:** Zoom, Google Meet, Microsoft Teams, OBS Studio and your browser see a camera called “Camora”.
- **Private:** no account, no cloud. The video goes straight from your phone to your computer, and the Wi-Fi link is encrypted.
- **Free**, with no ads and no watermark.

## Quick start

1. **Install** Camora on your computer and on your phone (links above).
2. **Connect:** plug the phone in with a USB cable (turn on USB debugging once: Camora walks you through it), or pair over Wi-Fi with the 6-digit code.
3. **Start streaming** on the phone, then pick **“Camora”** as the camera in your video app.

The [setup guide](https://www.getcamora.in/guide) has every step, and help for when something doesn't work. App-specific guides: [Zoom](https://www.getcamora.in/zoom) · [Google Meet](https://www.getcamora.in/google-meet) · [Microsoft Teams](https://www.getcamora.in/microsoft-teams) · [OBS](https://www.getcamora.in/obs) · [Ubuntu](https://www.getcamora.in/ubuntu) · [Windows 11](https://www.getcamora.in/windows).

### Install notes

- **Windows:** SmartScreen may warn that the installer is from an unknown publisher (it isn't code-signed yet). Choose **More info → Run anyway**. The installer asks for administrator permission once, to add the Camora camera for all apps.
- **Ubuntu:** `sudo apt install ./Camora-Ubuntu-24.04.deb` (or `-26.04`). It installs adb and turns on the “Camora” camera; it works with Secure Boot on Ubuntu's own kernels.
- **Android:** allow your browser or Files app to install apps when asked.

## FAQ

**Is it free?** Yes. No account, no subscription, nothing locked. If it's earned a place in your setup, you can [pay what it's worth to you](https://www.getcamora.in/support).

**Does it work on Windows 10, macOS or with an iPhone?** Not yet: Camora needs Windows 11 or Ubuntu, and an Android phone.

**Does it send the phone's microphone too?** Not yet: Camora sends video. Use your computer's or headset's microphone.

**How does it compare to DroidCam or Iriun?** See [Camora vs DroidCam](https://www.getcamora.in/vs/droidcam) and [Camora vs Iriun](https://www.getcamora.in/vs/iriun).

## Help and contact

Something not working? Check the [troubleshooting guide](https://www.getcamora.in/guide#help), or [open an issue](https://github.com/sohail300/camora-releases/issues) in this repository. You can also write to **sohail@getcamora.in**.

[Privacy](https://www.getcamora.in/privacy) · [Terms](https://www.getcamora.in/terms)

---

<sub>Camora is made by Byte Studio. Zoom, Google Meet, Microsoft Teams, OBS Studio, Windows, Ubuntu and Android are trademarks of their respective owners.</sub>
