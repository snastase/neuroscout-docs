# Overview

[![Documentation Status](https://readthedocs.org/projects/pyns/badge/?version=latest&style=flat)](https://pyns.readthedocs.io/en/latest/?badge=latest) [![PyPI version](https://badge.fury.io/py/pyNS.svg)](https://badge.fury.io/py/pyNS)

__pyNS__ is the Python client library for accessing the [Neuroscout API](https://neuroscout.org/api).

At it's most basic, __pyNS__ facilitates making HTTP requests to the API, by pre-formulating requests, and making it accessible via an easy-to-use, Pythonic API. In addition, __pyNS__ supports Neuroscout applications that interact with the API, such as [Neuroscout-CLI](../cli/intro.md).

For the end user, __pyNS__ enables flexibly querying and interaction with the Neuroscout API, enabling several advanced cases not supports by the web-based application such as:


* Downloading data from Neuroscout, including full predictor time courses
* Batch-creation of analyses-- particular useful for meta-analytic workflows which test the same analysis across datasets
* Full flexiblity in specification of BIDS StatsModels [https://bids-standard.github.io/stats-models/]. This enables statistical models which may not be supported by the web app, but are valid and executabl models.

In addition, for developers __pyNS__ may enable the development of novel experimental applications that use Neuroscout API's data. For example, there is ongoing work to develop an encoding analysis workflow in Neuroscout using __pyNS__. 


### Documentation

The pyNS library provides its own complete documentation at [ReadTheDocs](https://pyns.readthedocs.io/en/latest/). Please refer to that for installation instructions, quickstart, and in depth reference.