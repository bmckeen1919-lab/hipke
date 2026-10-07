# Hipke

A generated language (`conlang` toolkit), translating *The Quiet Morning*.

## Regenerate

    conlang generate --spec spec/hipke.yaml --out out/hipke.json

## Translate

    conlang translate --workspace . --glosses the_quiet_morning_hipke.tsv \
      --sentences the_quiet_morning_sentences.csv --out the_quiet_morning_hipke.csv
    conlang validate-translation --csv the_quiet_morning_hipke.csv
