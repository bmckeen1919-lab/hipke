# Mission: translate *The Quiet Morning* into Hipke

**Hipke** is a constructed language produced by the `conlang` toolkit — a seeded base (inventory and syllable shapes) generated and then deliberately extended. This project translates the fixed 111-sentence English story *The Quiet Morning* into Hipke.

## Success measures

- All **111 sentences** translated in `the_quiet_morning_hipke.csv` (`index,english,hipke`).
- Every form legal under Hipke's inventory and phonotactics; untranslatable items quarantined as `[slot]`.

## Sources of truth

- The model `out/hipke.json`; the frozen spec `spec/hipke.yaml`.
- The toolkit — the `conlang` package.
