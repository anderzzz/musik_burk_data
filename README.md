# MusikBurk Data

This repository is the public companion to [MusikBurk](https://github.com/anderzzz/musik_burk), a kid-friendly local music playbox for recording, collecting, and mixing audio samples.

Here you will find:
- **Shelf collections** — ready-made sample libraries you can import directly into MusikBurk
- **Nursery patches** — synthesizer setups for the node-based Nursery (Plantskolan) view
- **Issue tracker** — file bug reports and feature requests in the [Issues tab](https://github.com/anderzzz/musik_burk_data/issues)

---

## Shelf Collections (`hyllan_zipped/`)

Shelf exports are `.zip` files. Import them via **Hyllan → Import** in MusikBurk to add the samples to your local library.

| File | Contents |
|------|----------|
| `trummor_bas_v0.2.0.zip` | ~10 short clips covering a basic acoustic drum kit (kick, snare, hi-hat, etc.) |
| `gitarr-orgel-ackord.zip` | 12 chords played on acoustic guitar (two voicings) and electric organ, in both short and long versions |
| `space_guitar_notes.zip` | Individual notes played on a space-guitar synthesizer, spanning several octaves |
| `trum_slingor.zip` | Ready-to-use drum loops |

### How to download a zip file

1. Click the file name in the table above (or navigate to `hyllan_zipped/` in the file list).
2. On the file page, click the **download icon** (⬇) in the top-right corner, labelled *"Download raw file"*.
3. Save the `.zip` somewhere on your computer.
4. Open MusikBurk, go to **Hyllan**, and choose **Import** to load the collection.

> **Do not use** *"Download ZIP"* from the green *Code* button — that downloads the entire repository, not a single file.

---

## Nursery Patches (`plantskolan_procedures/`)

Nursery patches are plain JSON files (`.musikburk-patch.json`). Import them via **Plantskolan → Load patch** in MusikBurk.

| File | Description |
|------|-------------|
| `elorgel.musikburk-patch.json` | Simple electric organ with light vibrato — a saw + square oscillator chain through a Moog filter |

### How to use a patch file

**Option A — Download the file**

1. Click the file name in the table above.
2. Click **Download raw file** (⬇) in the top-right corner.
3. In MusikBurk, open **Plantskolan** and choose **Load patch**, then select the downloaded file.

**Option B — Copy and paste**

Because patch files are plain text, you can also:

1. Click the file name in the table above.
2. Click **Raw** to see the raw JSON.
3. Select all (`Ctrl+A` / `Cmd+A`), copy, and paste into MusikBurk's **Load patch → Paste JSON** field.

---

## Reporting Issues

Found a bug or have a feature idea? Open an issue in the [Issues tab](https://github.com/anderzzz/musik_burk_data/issues). Please include your operating system and a short description of what happened.
