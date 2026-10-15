# MyTunnel — yuklab olish

[MyTunnel](https://mytunnel.uz) — lokal portingizni `https://<subdomen>.mytunnel.uz` orqali internetga ochadigan desktop ilova (ngrok muqobili).

Bu repo faqat tayyor o'rnatuvchilar uchun. Eng so'nggi versiya: **[Releases → Latest](../../releases/latest)**

| Tizim | Qaysi faylni yuklab olish kerak |
| --- | --- |
| Windows 10/11 | `MyTunnel-<versiya>-win-x64.exe` |
| macOS (Apple M1/M2/M3/M4) | `MyTunnel-<versiya>-mac-arm64.dmg` |
| macOS (Intel) | `MyTunnel-<versiya>-mac-x64.dmg` |
| Linux (istalgan distributiv) | `MyTunnel-<versiya>-linux-x86_64.AppImage` |
| Ubuntu / Debian | `MyTunnel-<versiya>-linux-amd64.deb` |

## O'rnatish

**Windows:** `.exe` ni ishga tushiring. "Windows protected your PC" chiqsa: *More info* → *Run anyway*.

**macOS:** `.dmg` ni oching va MyTunnel'ni *Applications* ga torting. Birinchi ochishda ilovani o'ng tugma bilan bosib → *Open*. "MyTunnel is damaged" desa, Terminal'da:
```bash
xattr -cr /Applications/MyTunnel.app
```

**Linux (AppImage):**
```bash
chmod +x MyTunnel-*.AppImage && ./MyTunnel-*.AppImage
```

**Ubuntu / Debian:**
```bash
sudo apt install ./MyTunnel-*-linux-amd64.deb
```

O'rnatgach, ilovada ro'yxatdan o'ting yoki Google / Telegram orqali kiring va **Yangi tunnel** tugmasini bosing.
