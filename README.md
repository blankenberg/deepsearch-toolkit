# DeepSearch Toolkit

[![PyPI version](https://img.shields.io/pypi/v/deepsearch-toolkit)](https://pypi.org/project/deepsearch-toolkit/)
[![PyPI - Python Version](https://img.shields.io/pypi/pyversions/deepsearch-toolkit)](https://pypi.org/project/deepsearch-toolkit/)
[![License MIT](https://img.shields.io/github/license/ds4sd/deepsearch-toolkit)](https://opensource.org/licenses/MIT)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Docs](https://img.shields.io/badge/website-live-brightgreen)](https://ds4sd.github.io/deepsearch-toolkit/)


*Interact with the DeepSearch platform for new knowledge explorations and discoveries*


The Deep Search Toolkit is a Python SDK allowing a user to interact with the Deep Search platform. The Toolkit provides easy-to-use functionalities for several common processes such as document conversion, graph creation and querying.


[Learn about IBM Deep Search](https://ds4sd.github.io/)


## Quick links

- [Github repository](https://github.com/ds4sd/deepsearch-toolkit)
- [Documentation](https://ds4sd.github.io/deepsearch-toolkit/)


## Install

Using `poetry` in your project? Add the toolkit with:
```console
$ poetry add deepsearch-toolkit
```

New to `poetry`? Visit https://python-poetry.org/ or our [CONTRIBUTING.md](CONTRIBUTING.md) section.


Using `pip`:
```console
$ pip install deepsearch-toolkit
```

### Requirements

Python 3.8+


## Start using the toolkit

 ```console
// Login to Deep Search, see https://ds4sd.github.io/deepsearch-toolkit/getting_started/authentication/
$ deepsearch login
...


// Convert a document
// for more details, see https://ds4sd.github.io/deepsearch-toolkit/guide/convert_doc/
$ deepsearch documents convert -p 1234567890abcdefghijklmnopqrstvwyz123456 -u https://arxiv.org/pdf/2206.00785.pdf
--------------------------------------------------------------------------------------
                          Welcome to the Deep Search Toolkit
--------------------------------------------------------------------------------------
Submitting input:   100%|█████████████████████████████████████████████████████████████| 1/1 [00:01<00:00,  1.23s/it]
Converting input:   100%|█████████████████████████████████████████████████████████████| 1/1 [00:25<00:00, 25.61s/it]
Downloading result: 100%|█████████████████████████████████████████████████████████████| 1/1 [00:01<00:00,  1.50s/it]

Total online documents:            0001
Successfully converted documents:  0001(100%)
Run time:                          29.51 seconds
```


## Get help and support

Please feel free to connect with us using the [discussion section](https://github.com/DS4SD/deepsearch-toolkit/discussions).


## Contributing

Please read [Contributing to DeepSearch Toolkit](./CONTRIBUTING.md) for details.


## References

If you use `DeepSearch` in your projects, please consider citing the following:

```bib
@software{DeepSearch Toolkit,
author = {DeepSearch Team},
month = {6},
title = {{DeepSearch Toolkit}},
url = {https://github.com/DS4SD/deepsearch-toolkit},
version = {main},
year = {2022}
}
```

## License

The `DeepSearch Toolkit` codebase is under MIT license.
For individual model usage, please refer to the model licenses found in the original packages.
