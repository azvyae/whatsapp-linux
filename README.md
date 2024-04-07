# WhatsApp Linux
WhatsApp Linux client built with Electron, forked from Alberto Mimbrero's Whatsapp Desktop Linux

## 📜 Disclaimer
This just loads https://web.whatsapp.com/ with some extra features, but never changing the content of the official webpage (html, css nor javascript). Linux users just can't install any official app, and whatsapp-deskop-linux is running the official web client.

This wrapper is not verified by, affiliated with, or supported by WhatsApp Inc.

## 💾 Installation
### 🖱️✔️ Recommended: Flathub
The official Flatpak build is updated instantly after every update.

<a href="https://flathub.org/apps/details/io.github.azvyae.WhatsappLinux"><img src="https://flathub.org/assets/badges/flathub-badge-en.png" width="250"></a>

### 🖱️ AppImage
The AppImage build is attached to every release. Check the [releases page](https://github.com/azvyae/whatsapp-linux/releases).
Download the .AppImage file, mark it as executable and double click it. [Check this video tutorial](https://www.youtube.com/watch?v=nzZ6Ikc7juw).

## :hammer: CLI arguments
- `--start-hidden`: starts WhatsApp hidden in tray.

## :construction: Development
PR and forks are welcome!

1. Clone the repo
```bash
git clone https://github.com/azvyae/whatsapp-linux.git
cd whatsapp-linux
```

2. Install dependencies
```bash
bun install
```

3. Run or build
```bash
bun start # compile and run
bun run build # compile and build
```
