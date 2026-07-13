# Contribuzioni a DataCivicLab

Elenco delle issue e PR completate per [dataset-incubator](https://github.com/dataciviclab/dataset-incubator).

## 2026

| Issue | Descrizione | PR |
|-------|------------|-----|
| [#512](https://github.com/dataciviclab/dataset-incubator/issues/512) | Verifica 9 CIG con importi anomali in anac-bandi-gara (ANAC 2025). Identificati 1 caso reale, 6 errori di codifica, 2 casi dubbi. Documentato in notes.md. | [#608](https://github.com/dataciviclab/dataset-incubator/pull/608) |
| [#596](https://github.com/dataciviclab/dataset-incubator/issues/596) | Intake sbarchi-migranti-italia (onData). Candidate con pipeline toolkit su sbarchi-per-giorno (DuckDB). Review Gabrymi93: ridotto a soli sbarchi giornalieri. PR mergiata. | [#611](https://github.com/dataciviclab/dataset-incubator/pull/611) |
| [#494](https://github.com/dataciviclab/dataset-incubator/issues/494) | Intake ACI prime iscrizioni autovetture 2017-2024. 8 fonti HTTP, clean solo comuni, schema anno/comune/provincia/alimentazione. PR mergiata. | [#624](https://github.com/dataciviclab/dataset-incubator/pull/624) |
| [#588](https://github.com/dataciviclab/dataset-incubator/issues/588) | Verifica pipeline Regionali #588. Script plugin locale per preprocess.py, fix clean.read.mode. | [#633](https://github.com/dataciviclab/dataset-incubator/pull/633) |
| — | Intake elezioni Europee (1979-2024): 10 anni, script preprocess.py con COL_MAP esteso per DESCR*. | [#633](https://github.com/dataciviclab/dataset-incubator/pull/633) |
| — | Intake referendum (1995-2022): 8 anni, multi-formato TXT/CSV, gender-split. | [#633](https://github.com/dataciviclab/dataset-incubator/pull/633) |
| — | Intake elezioni Comunali (2016-2024): 7 anni, merge scrutini + liste via lookup. | [#633](https://github.com/dataciviclab/dataset-incubator/pull/633) |
| [#413](https://github.com/dataciviclab/dataset-incubator/issues/413) | Intake istat-asia-ul (DBnomics). Unità locali 2018-2020 per comune/ATECO. Preprocess parallelo 6 workers. PR mergiata. | [#642](https://github.com/dataciviclab/dataset-incubator/pull/642) |
| [#628](https://github.com/dataciviclab/dataset-incubator/issues/628) | Intake mur-immatricolati (CKAN MUR). Immatricolati universitari 1998-2025 per classe/genere. Review Gabrymi93: riscritto in http_file. In review. | [#643](https://github.com/dataciviclab/dataset-incubator/pull/643) |
| [#454](https://github.com/dataciviclab/dataset-incubator/issues/454) | Intake personale-ssn (Ministero Salute). Personale SSN 2010-2021 per ruolo/genere. 3 file XLS/XLSX. In review. | [#644](https://github.com/dataciviclab/dataset-incubator/pull/644) |
| [#489](https://github.com/dataciviclab/dataset-incubator/issues/489) | Fix skip GCS push per compose dataset. In review. | [#641](https://github.com/dataciviclab/dataset-incubator/pull/641) |
| [#629](https://github.com/dataciviclab/dataset-incubator/issues/629) | Intake mur-iscritti (CKAN MUR). Iscritti universitari 2000-2025 per ateneo/genere. http_file con URL CSV diretto. In review. | [#646](https://github.com/dataciviclab/dataset-incubator/pull/646) |
| [#523](https://github.com/dataciviclab/dataset-incubator/issues/523) | Intake elezioni-politiche (Eligendo DAIT). Camera+Senato 1948-2022 per comune. 38 ZIP unificati da preprocess.py. In review. | [#647](https://github.com/dataciviclab/dataset-incubator/pull/647) |
| — | Analisi Discussione #396 "La PA è sempre più donna?". Trend 2010-2023: +4.9pp donne nella PA. Output pubblicato. | [#396](https://github.com/dataciviclab/dataciviclab/discussions/396#discussioncomment-17605302) |
