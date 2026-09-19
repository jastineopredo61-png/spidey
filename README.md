# RetroLens 🖐️✨

A real-time hand-gesture portal filter, built with Python + MediaPipe.

Spread both hands to open a portal — the area inside gets filtered (dual-tone, thermal, sketch, glitch, etc). Pinch your thumb and pinky to switch filters.

---

**Install** (Python 3.8–3.11):
```bash
pip install -r requirements.txt
```
> ⚠️ Apple Silicon users: don't upgrade mediapipe past the pinned version (`0.10.9`) — newer releases are buggy on ARM Macs.

**Run:**
```bash
python3 Retrolens.py   # Mac/Linux
python Retrolens.py    # Windows
```

**Controls:**
- Spread both hands → open portal
- Pinch thumb + pinky → switch filter
- Fist both hands / press `C` → toggle 2D/3D mode
- `N`/`P` → next/previous filter, `S` → screenshot, `Q` → quit

Built while learning OpenCV + MediaPipe.

---

MIT License
