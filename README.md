# IPA Chart

A colourful, interactive International Phonetic Alphabet chart in a single HTML page.

## Features

- Every chart from the official IPA Chart: pulmonic and non-pulmonic consonants, vowels, other symbols, diacritics, suprasegmentals, and tones and word accents (178 symbols).
- Explore panels that explain place, manner and voicing (and vowel height, backness and rounding) in plain language and highlight the matching symbols.
- A detail drawer for each symbol with how it's made, official recordings, examples, Unicode code point and IPA number.
- Search (`/`), a transcription tray, and an ear-training quiz.

## Run locally

It's a static page with no build step:

```sh
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Credits

- Chart content: [IPA Chart](https://www.internationalphoneticassociation.org/content/ipa-chart), available under a Creative Commons Attribution-Sharealike 3.0 Unported License. Copyright © 2020 International Phonetic Association.
- Recordings by John Esling, Jill House, Peter Ladefoged and John Wells, played from the IPA's [interactive chart](https://www.internationalphoneticassociation.org/IPAcharts/IPA_charts_EI/IPA_charts_EI.html).
