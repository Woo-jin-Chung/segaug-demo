# Segment Augmentation — Decoding Examples

Held-out decoding examples for
**Learning Alignment from Limited Clinical sEEG Recordings via Segment Augmentation**.

**Demo page:** open `index.html`, or browse the hosted version once GitHub Pages is enabled.

## What is here

| Path | Contents |
|---|---|
| `index.html` | the page: title, abstract, and the 11 held-out sentences of fold 0 |

Each sample shows the reference sentence and the output of the same CTC decoder trained
on 5.0 minutes of clinical sEEG, once with segment augmentation (word-level Crop with Window)
and once without augmentation. For every row the page lists the decoded Korean, the emitted
phonemes, and the word timing against the word boundaries from forced alignment of the audio.

The page is self-contained: data are embedded in `index.html`, and only the Nanum Myeongjo
web font is loaded from Google Fonts.
