# The corpus as a network

[![GitHub issues](https://img.shields.io/github/issues/maehr/the-corpus-as-a-network.svg)](https://github.com/maehr/the-corpus-as-a-network/issues)
[![GitHub forks](https://img.shields.io/github/forks/maehr/the-corpus-as-a-network.svg)](https://github.com/maehr/the-corpus-as-a-network/network)
[![GitHub stars](https://img.shields.io/github/stars/maehr/the-corpus-as-a-network.svg)](https://github.com/maehr/the-corpus-as-a-network/stargazers)
[![GitHub license](https://img.shields.io/github/license/maehr/the-corpus-as-a-network.svg)](https://github.com/maehr/the-corpus-as-a-network/blob/main/LICENSE)
[![DOI](https://zenodo.org/badge/577453842.svg)](https://zenodo.org/badge/latestdoi/577453842)

*Turning source documents into a graph with NLP*

[Moritz Mähr](https://orcid.org/0000-0002-1367-1618) (University of Bern)

December 12, 2022

Lecture series "Einblicke in die Digital Humanities" (fall semester 2022)

Abstract: For the research project "The Evolution of Internet Governance" at the University of Bern, a corpus was compiled. The born digital sources date from the years between 1969 and 1999 and are relatively homogeneous. This allowed to build different network representations (graphs) of the indicated human and non-human actors, locations and events from the corpus using NLP (rule-based annotations as well as automated Named Entity Recognition). The process of annotating the corpus and constructing bipartite graphs is the subject of this lecture.

## Installation

Use the package manager [poetry](https://python-poetry.org/) to install the dependencies.

```bash
poetry install
```

## Usage

```bash
poetry run jupyter notebook notebooks/the-corpus-as-a-network.ipynb
```

| Nbviewer | Jupyter Notebook | Jupyter Lab | HTML |
| ---      | --               | ---         | ---  |
| [the-corpus-as-a-network.ipynb](https://nbviewer.jupyter.org/github/maehr/the-corpus-as-a-network/blob/main/notebooks/the-corpus-as-a-network.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/maehr/the-corpus-as-a-network/main?filepath=notebooks%2Fthe-corpus-as-a-network.ipynb) | [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/maehr/the-corpus-as-a-network/main?labpath=notebooks%2Fthe-corpus-as-a-network.ipynb) | [HTML](https://maehr.github.io/the-corpus-as-a-network/) |

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/maehr/the-corpus-as-a-network/tags).

## Authors and acknowledgment

- **Moritz Mähr** - *Initial work* - [maehr](https://github.com/maehr)

See also the list of [contributors](https://github.com/maehr/the-corpus-as-a-network/graphs/contributors) who participated in this project.

## License

[BSD-3-clause](https://choosealicense.com/licenses/bsd-3-clause/)
