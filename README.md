![Supported Python Versions](https://img.shields.io/badge/Python->=3.6-blue.svg?logo=python&logoColor=white)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

# Machine Learning Handbook

This repository contains the source files for the [Machine Learning Handbook](https://www.bpesquet.fr/mlhandbook), my textbook for teaching Machine Learning. More info [here](index.md).

## Development notes

### Generating the site

The [website](https://www.bpesquet.fr/mlhandbook) is generated by [Jupyter Book](https://jupyterbook.org). After installing it, execute the following command in the root folder to generate the HTML output in the `_build` subdirectory:

```bash
jupyter-book build .
```

A [GitHub action](.github/workflows/deploy.yaml) is used to publish this output as a website.

### Adding or updating katas

The practical challenges, named _katas_, are generated with [nbgrader](https://nbgrader.readthedocs.io/) and contain missing answers. Teacher versions (corrections) live in a separate private repository.

The [mlkatas](https://github.com/bpesquet/mlkatas) repository is outdated. Its content has been merged into this repository.

### Exporting a notebook to a PDF file

Use [nbconvert](https://nbconvert.readthedocs.io) in the same directory as the source file:

```bash
jupyter nbconvert --to PDF <chapter_file_name>.ipynb
```

> For now, GIF files must be replaced by their PNG counterparts before launching the conversion process.
