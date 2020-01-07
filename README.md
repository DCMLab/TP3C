# TP3C corpus
The TP3C ("tonal pitch class counts corpus") is a dataset of tonal pitch-class counts of Western classical music pieces over a large historical range. It was initially created for [Moss (2919)][1]

If you find errors or want to contribute data to the corpus, see under [Contributions](#Contributions). If you use this corpus in a research project, see below how to [cite](#Citation) the dataset.

## Tonal pitch-classes
- difference to MIDI
- important for music cognition, music information retrieval, and music theory (prediction, tension, voice-leading)
- TPCs can be arranged on the line of fifths
- the corpus contains counts for TPCs from Fbb to B##

## Data acquisition and preprocessing

- Describe the data sources

## Corpus description
The corpus is given as a tab-separated `.tsv` file with the following columns:

- `composer`: last name of composer
- `composer_first`: first name(s) of composer
- `work_group`: larger collection to which piece belongs (e.g. "Préludes", "Etudes"...)
- `work_catalogue`: work catalogue string like "Op.", "BWV", "KV", etc.
- `opus`: opus no.
- `no`: number, as in "Op. 4, no. 3"
- `mov`: movement number
- `title`: title of piece
- `composition`: date of composition
- `publication`: date of publication
- `source`: abbreviated source from which file and counts were originally obtained (see below)
- `display_year`: unique year per piece; if composition year is not given, publication year is used; if neither is given, the middle of the composer's life is used
- `Fbb` ... `B##`: counts of tonal pitch classes 

## Contributions

- To report errors, e.g. in composition dates, please create an [issue](https://github.com/DCMLab/tpc_corpus/issues) describing the error.
- You can contribute new data in the same way
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

## References

[1]: https://doi.org/10.5075/epfl-thesis-9808	"Moss, F. C. (2019). Transitions of Tonality: A Model-Based Corpus Study [Doctoral Dissertation, École Polytechnique Fédérale de Lausanne]. https://doi.org/10.5075/epfl-thesis-9808"

