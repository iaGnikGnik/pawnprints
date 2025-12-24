# 🏰 PawnPrints

**PawnPrints** is a professional-grade chess tool that analyzes a player’s games to reveal their style and repeated positions. Built for players, coaches, and creators who work with PGNs.

---

## ✨ Features

- 📂 Load PGN files and browse games with scrollable, annotated board
- 🧠 Analyze a player's games for repeated positions
- 📌 Export FENs of common positions to `.pgn` for use in SCID or other tools
- 🎯 Fully native Linux app with icon, launcher, and terminal command
- 🔁 Reproducible behavior — no Python setup required

---

## 📥 Download & Install (Ubuntu/Debian)

1. [Download the latest `.deb` release](https://github.com/iaGnikGnik/pawnprints/releases/latest)
2. Install it with:

```bash
sudo dpkg -i ~/Downloads/pawnprints_1.0.1.deb

    Launch it from your App Menu or by typing:

pawnprints

🛠 System Requirements

    Ubuntu 20.04+ or any Debian-based distro

    64-bit system (amd64)

🧪 How It Works

PawnPrints parses your PGN collection, isolates positions a selected player hits often, and lets you:

    Scroll through occurrences

    Export to .pgn as mini-games with FEN + comments

    Review your tendencies and improve

Ideal for use with SCID, lichess.org studies, or opening prep.

---

## PawnPrints v2.0.0

PawnPrints v2.0 is the first full desktop application release of PawnPrints.

It enables player style analysis based on recurring board positions, optional
engine enrichment, and comparison of player tendencies across PGNs.

##Features
- Player style analysis using common positions
- Optional Stockfish engine analysis
- Compare mode (common positions across two PGNs)
- Download games from:
    - Lichess
    - Chess.com
    - The Week In Chess (TWIC)
- Export analyzed and flagged PGNs
- Portable Linux AppImage (no installation required)

##Running (Linux AppImage)
chmod +x PawnPrints-v2.0.0-x86_64.AppImage
./PawnPrints-v2.0.0-x86_64.AppImage

Known Issues
After closing a PGN and loading a new one, exporting results without restarting the application may export results from a previous analysis session.
Restarting PawnPrints resolves the issue.
This will be fixed in a future release.

📬 Contact & Support
Maintainer

King King
📧 kkingpublishing@gmail.com

Feel free to open an issue for bugs or feature requests.

License

All rights reserved — for personal and educational use only.
