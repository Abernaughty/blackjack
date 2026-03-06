# Blackjack — Two Implementations

The same Blackjack game implemented in two different environments — a desktop GUI and a
web browser. Both versions share the same rules and game logic but take fundamentally
different approaches to the UI and platform.

## Implementations

| | [`/python`](./python) | [`/web`](./web) |
|---|---|---|
| **Platform** | Desktop | Browser |
| **Language** | Python | HTML / CSS / JavaScript |
| **UI** | Tkinter GUI | Vanilla JS |
| **Persistence** | File-based (`bj_balance.txt`) | localStorage |
| **Run** | `python Blackjack.py` | Open `index.html` |

## `/python` — Desktop App

A Python + Tkinter implementation with a graphical card interface, betting system, and
balance tracking. Built as a learning project in Python GUI development.

**Requirements:** Python 3.6+, Pillow

```bash
cd python
pip install Pillow
python Blackjack.py
```

## `/web` — Browser Version

A full web port of the same game — converted from Python/Tkinter to HTML, CSS, and
JavaScript. Adds features like Split, Double Down, and Surrender.
Also deployed at [blackjack.maber.io](https://blackjack.maber.io/).

```bash
cd web
# Open index.html directly in a browser — no build step required
```

## License

MIT
