# OZX SOUNDCRAFT: 31-Bands Audio Terminal

**OZX SOUNDCRAFT** iku *Web Audio API* terminal-style player sing dirancang kanggo para audiophile sing pengen kontrol frekuensi *real-time* tanpa *bloatware* pabrikan.

## Filosofi "Waton Fungsi"
* **Raw & Direct**: Dudu player pabrikan sing kakehan *skin* ora guno. Iki *pure logic* ing terminal.
* **AudioContext-Driven**: Nggunakake 31 `BiquadFilterNode` sing diproses langsung ing browser kanggo presisi maksimal.
* **Terminal Aesthetic**: Desain ijo stabilo kanggo fokus maksimal ing *gain staging* lan frekuensi.

## Fitur Utama
* **31-Band Equalizer**: *Fine-tuning* frekuensi saka 20Hz nganti 20kHz.
* **Terminal Shortcuts**: 
    * `[SPACE]`: Play/Pause
    * `[S]`: Stop
    * `[N]/[P]`: Next/Prev Track
    * `[R]`: Reset EQ
    * `[+/-]`: Volume Control
* **High Fidelity Focus**: Ngetes *dynamic range* lagu kanthi presisi dhuwur.

## Struktur Direktori
```text
ozx-soundcraft/
├─ audio/          # Media simpenan (Ogg/Wav)
├─ src/            # Core logic (JS Web Audio API)
├─ include/        # Dependencies/Helper scripts
├─ build/          # Build output
└─ README.md       # Dokumentasi iki


# equalizer-31-bands
ProSound Equalizer 31-bands OZXLabz SoundCraftman

###
## masterpiece-audio/
- ├─ audio/         # semua file .ogg / .wav
- │    ├─ track1.ogg
- │    └─ track2.ogg
- ├─ src/           # source code (C++ / JS / HTML)
- │    └─ main.cpp
- ├─ include/       # header / library tambahan
- ├─ build/         # optional: hasil compile
- └─ README.md

