# INJ3CT0R v1.0 - Steam Lua Hacker

```
  ██████ ▄▄▄█████▓▓█████ ▄▄▄ ███▄ ▄███▓
▒██ ▒ ▓ ██▒ ▓▒▓█ ▀▒████▄ ▓██▒▀█▀ ██▒
░ ▓██▄ ▒ ▓██░ ▒░▒███ ▒██ ▀█▄ ▓██ ▓██░
  ▒ ██▒░ ▓██▓ ░ ▒▓█ ▄░██▄▄▄▄██ ▒██ ▒██
▒██████▒▒ ▒██▒ ░ ░▒████▒▓█ ▓██▒▒██▒ ░██▒
```

**By VENKAT** | *Chennai Underground* | 2026

### What It Does
Standalone .exe that **hacks Steam locally** — fetches Lua/manifests from cysaw.pw, injects keys to config.vdf, creates appmanifest.acf, and dumps game folder. No traces, no mercy.

### Features
- **Zero-Click Injection**: Enter AppID → Done.
- **Bundled Chaos**: ZIP to Downloads, game folder in script dir.
- **Key Extraction**: Parses Lua like a boss.
- **Portable**: Runs anywhere, no Python.

### Quick Hack
1. Run `injector.exe` (as admin).
2. Enter AppID (e.g., `730`).
3. Watch magic:
   ```
   Target: Counter-Strike 2
   Downloaded 730.zip
   Injected 3 keys
   Created appmanifest_730.acf
   SUCCESS!
   ```
4. Restart Steam → Loot acquired.

### Targets
- `STEAM_PATH = r"C:\Program Files (x86)\Steam"` — Change if custom install.

### Warnings
- **Local Only**: Works on this PC. Multi-device? Dream on.
- **Ban Risk**: Valve sniffs this — use throwaway account.
- **Malware Alert**: Lua files can bite. Scan everything.
- **Legal**: Educational tool. Don't be a pirate, buy on sale.

**License**: MIT — Fork it, break it, own it.

*Hacked by VENKAT | No Logs, No Mercy | 2026* 🏴‍☠️
