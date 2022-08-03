
```{toctree}
---
hidden: true
includehidden: true
titlesonly: true
---
```

![logo](static/neuroscout_docs_paths.svg)

# What is Neuroscout?

Neuroscout is an end-to-end platform for analysis of naturalistic public fMRI datasets.
With Neuroscout, you can choose among [dozens of naturalistic fMRI datasets](https://neuroscout.org/datasets) and easily build statistical models [on your browser](web/builder/intro.md) to analyze them. 
We provide [hundreds of pre-extracted predictors](https://neuroscout.org/predictors), but you can also upload custom features.
Analyses can be downloaded and executed it in one line of code using Neuroscout-CLI, and results are automatically uploaded to [NeuroVault](https://www.neurovault.org/).

![fig2a](https://user-images.githubusercontent.com/2774448/163874691-c44ebc96-dd3f-4642-bf5a-0d1abd4ddbad.png)

Neuroscout leverages state-of-the-art machine learning models to automatically annotate naturalistic stimuli, and uses [BIDS Stats Models](https://fitlins.readthedocs.io/en/latest/model.html) and [FitLins](https://github.com/poldracklab/fitlins) to specify and consume statistical models.
[Analysis execution](cli/intro.md) is achieved with _minimal configuration_ using self-contained bundles and run-time data retrieval. Containerized _model-fitting pipelines_  minimize software dependencies and ensure _high portability_ across execution environments.

---

::::{grid} 1 1 1 2
:gutter: 3 3 3 3

:::{grid-item-card}
:shadow: md
:class-header: bg-light
**📖 Learn more**
^^^
**[Ecosystem](overview/ecosystem.md)**: Get familiar with Neuroscout

**[Paper](https://doi.org/10.1101/2022.04.05.487222)**: Read for an in-depth dive

**[Browse](https://neuroscout.org/public)**: Browse public analyses

:::

:::{grid-item-card}
:shadow: md
:class-header: bg-light
**🚀 Get started**
^^^
**[neuroscout.org builder](web/builder/intro.md)**: Create a custom analysis

**[Neuroscout-CLI](cli/intro.md)**: Run your analysis

**[Python API](python_api/overview.md)**: Advanced usage

:::

::::


## Where can I get more help?
Connect with us by asking a question on [NeuroStars](https://neurostars.org/tag/neuroscout) or [open an issue on GitHub](https://github.com/neuroscout/neuroscout/issues)
to report bugs or request new features. 


[![License](https://img.shields.io/github/license/neuroscout/neuroscout)](https://github.com/neuroscout/neuroscout)
