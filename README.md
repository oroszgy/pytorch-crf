# pytorch-crf

Conditional random field in [PyTorch](http://pytorch.org/).

[![Python versions](https://img.shields.io/pypi/pyversions/pytorch-crf.svg?style=flat)](https://img.shields.io/pypi/pyversions/pytorch-crf.svg?style=flat)

[![PyPI project](https://img.shields.io/pypi/v/pytorch-crf.svg?style=flat)](https://pypi.org/project/pytorch-crf)

[![Build status](https://github.com/kmkurn/pytorch-crf/actions/workflows/run_tests.yml/badge.svg)](https://github.com/kmkurn/pytorch-crf/actions/workflows/run_tests.yml)

[![Documentation status](https://img.shields.io/readthedocs/pytorch-crf.svg?style=flat)](https://pytorch-crf.readthedocs.io)

[![Code coverage](https://img.shields.io/coveralls/github/kmkurn/pytorch-crf.svg?style=flat)](https://coveralls.io/github/kmkurn/pytorch-crf)

[![License](https://img.shields.io/pypi/l/pytorch-crf.svg?style=flat)](https://choosealicense.com/licenses/mit/)

[![Built with Spacemacs](https://cdn.rawgit.com/syl20bnr/spacemacs/442d025779da2f62fc86c2082703697714db6514/assets/spacemacs-badge.svg)](http://spacemacs.org)

This package provides an implementation of linear-chain [conditional
random field](https://en.wikipedia.org/wiki/Conditional_random_field)
(CRF) in PyTorch. This implementation borrows mostly from [AllenNLP CRF
module
\<https://github.com/allenai/allennlp/blob/master/allennlp/modules/conditional_ra
ndom_field.py\>]() with some modifications.

# Documentation

<https://pytorch-crf.readthedocs.io/>

# License

MIT

# Contributing

Contributions are welcome! Please follow these instructions to install
dependencies and running the tests and linter.

## Installing dependencies

Make sure you setup a virtual environment with Python. Then, install all
the dependencies in `requirements.txt` file and install this package in
development mode.

    pip install -r requirements.txt
    pip install -e .

## Setup pre-commit hook

Simply run:

    ln -s ../../pre-commit.sh .git/hooks/pre-commit

## Running tests

Run `pytest` in the project root directory.

## Running linter

Run `flake8` in the project root directory. This will also run `mypy`,
thanks to `flake8-mypy` package.
