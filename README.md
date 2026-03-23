<p align="center">
  <img src="_assets/MusikBurk_full_logo_2.png" alt="MusikBurk" width="480">
</p>

<p align="center">
  <em>A kid-friendly, local-first music playbox for recording, collecting, and mixing audio samples.</em>
</p>

---

This is the public data companion to [MusikBurk](https://github.com/anderzzz/musik_burk). It contains ready-made content you can drop straight into the app — no setup beyond importing.

MusikBurk ships without built-in sounds by design (keeping the installer small and the app private). These packs are the cure for that cold start.

**What's here:**

- [Shelf collections](#-shelf-collections) — sample libraries importable into the Library (Hyllan) view
- [Nursery patches](#-nursery-patches) — synthesizer presets for the node-based Nursery (Plantskolan) view
- [Issues](#-reporting-issues) — bug reports and feature requests

---

## 🎵 Shelf Collections (`hyllan_zipped/`)

Shelf exports are `.zip` files. Import them via **Library → Import** in MusikBurk. Each pack appears as a set of named, categorised clips ready to use in the Workshop, Drum Studio, or Mixer.

| Pack | Contents |
|------|----------|
| [`musik_burk_trummor.zip`](hyllan_zipped/musik_burk_trummor.zip) | ~15 short clips covering a basic acoustic drum kit — kick, snare, hi-hat, cowbell, and more. A good starting point for Drum Studio. |
| [`space_guitar_notes.zip`](hyllan_zipped/space_guitar_notes.zip) | Individual notes of a space-guitar synthesizer spanning several octaves. Works well as a melodic instrument mapped across keys. |
| [`acoustic guitar.zip`](hyllan_zipped/acoustic%20guitar.zip) | Individual notes of an acoustic guitar, synthesized in part with Karplus-Strong physical modelling. |
| [`electrical_organ.zip`](hyllan_zipped/electrical_organ.zip) | 10-second sustaining notes from an electric organ synthesizer built with a Moog filter and Comb filters. Rich, harmonic texture. |

### Downloading a single zip

1. Click a pack name in the table above — this takes you to its file page on GitHub.
2. Click the **download icon** (⬇) in the top-right corner, labelled *"Download raw file"*. Do **not** click *"Raw"* — that opens the binary content in the browser instead of downloading it.
3. Save the `.zip` anywhere on your computer. **Safari users:** Safari may automatically unzip the file after download. If you end up with a folder instead of a `.zip`, re-compress it (right-click → *Compress*) before importing.
4. Open MusikBurk, go to **Library**, and choose **Import**.

> **Avoid** the green *Code → Download ZIP* button — that downloads the entire repository, not a single pack.

---

## 🌱 Nursery Patches (`plantskolan_procedures/`)

Nursery patches are plain JSON files (`.musikburk-patch.json`). They describe a synthesizer node graph — oscillators, noise sources, and filters wired together. Import them via **Nursery → Load patch**.

| Patch | Description |
|-------|-------------|
| [`elorgel.musikburk-patch.json`](plantskolan_procedures/elorgel.musikburk-patch.json) | A simple electric organ with light vibrato — a sawtooth and square oscillator chain routed through a Moog filter. |

### Using a patch file

**Option A — Download**

1. Click the patch name in the table above to go to its file page on GitHub.
2. Click the **download icon** (⬇) in the top-right corner, labelled *"Download raw file"*. This saves the `.json` file to your computer.
3. In MusikBurk, open **Nursery** and choose **Load patch**, then select the downloaded file.

**Option B — Copy and paste**

1. Click the patch name in the table above, then click **Raw** to see the plain JSON.
2. Select all (`Ctrl+A` / `Cmd+A`), copy, and paste into MusikBurk's **Load patch → Paste JSON** field.

---

## 🐛 Reporting Issues

Found a bug or have a feature idea? Open an issue in the [Issues tab](https://github.com/anderzzz/musik_burk_data/issues). Include your operating system and a short description of what happened (or what you'd like to see).
