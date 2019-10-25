# TPC corpus - a dataset of tonal pitch-class counts of Western classical music pieces
Corpus of tonal pitch-class (TPC) counts.

If you find errors or want to contribute data to the corpus, see under [Contributions](#Contributions). See below how to [cite](#Citation) the dataset.

## Tonal pitch-classes
- difference to MIDI
- important for music cognition, music information retrieval, and music theory (prediction, tension, voice-leading)
- TPCs can be arranged on the line of fifths
- the corpus contains counts for TPCs from Fbb to B##

## Data acquisition and preprocessing

- Describe the data sources

## Corpus structure
Description of the fields in the CSV.

- `composer`
- `composition_date`
- `publication_date`
- `tpcc_X`: count for tonal pitch-class X
- `tpcw_X`: normalized frequency of tonal pitch-class X
- `tpcd_X`: summed notated duration of tonal pitch-class X

## Contributions

- To report errors, e.g. in composition dates, please create an [issue](https://github.com/DCMLab/tpc_corpus/issues) describing the error.
- You can contribute new data.
- Do not hesitate to contact me for further questions: [fabian.moss@epfl.ch](mailto:fabian.moss@epfl.ch)

## Citation

If you use the corpus, please reference it as:

ZENODO REF IN APA

```bibtex
@dataset{tpc_corpusv1.0,
  author       = {Fabian C. Moss and
                  Martin Rohrmeier},
  title        = {TPC corpus},
  month        = oct,
  year         = 2019,
  publisher    = {Zenodo},
  version      = {1.0},
  doi          = {...},
  url          = {...}
}
```
