# Anthologia Palatina - Metrical Dataset

Metrical and prosodic dataset for Book I (Christian Epigrams) of the Anthologia Palatina (Codex Palatinus Graecus 23).

The dataset provides a quantifiable metrical and prosodic analysis of the Greek text as edited in *Anthologia Palatina. Book I. The Christian Poems* [cf. References], with manuscript variants noted wherever they diverge metrically from the edited text. The syllable hyphenation, metrical schemes, and all annotations were produced manually by the authors and verified with automated tooling.

## Contents

- `data/hex.csv` - Hexameter verses (337 verses)
- `data/iamb.csv` - Iambic trimeter verses (86 verses)
- `data/pentameter.csv` - Elegiac pentameter verses (77 verses)
- `data/anthologia_palatina.xlsx` - Source spreadsheet

## Parameters tracked

Metrical pattern, metrical and syntactic caesurae, diaereses, bridges, homodynia, and the position of word accents at caesurae.

## Viewer

An interactive viewer for this dataset is available at https://github.com/Vexiona/metrical-viewer.

## License

Copyright 2026 Simona Nicolae, Cristian Șimon. Licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
