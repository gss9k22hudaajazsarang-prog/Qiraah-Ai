IRAAH AI V3.1 — OFFLINE QURAN DATA BUILD

This build is based directly on the original V1 HTML. The V1 speech recognition and word-comparison functions are preserved.

IMPORTANT: You must add quran.json beside index.html. The ZIP intentionally does not contain a hand-reconstructed Quran text. Use the complete Quran JSON dataset linked in the instructions.

FILES:
- index.html — your V1 app + offline 114-surah loader
- quran.json — you will add this yourself

OFFLINE ARCHITECTURE:
Phone/browser -> GitHub Pages -> index.html -> local quran.json -> selected surah/ayah -> original V1 recognition/comparison.

Once quran.json is uploaded to the same GitHub folder as index.html, the Quran text itself does not need an API.
