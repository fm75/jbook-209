---
jupytext:
  text_representation:
    extension: .md
    format_name: myst
    format_version: 0.12
    jupytext_version: 1.6.0
kernelspec:
  display_name: Python 3
  language: python
  name: python3
---

# jbook-209
colab defaults on in jbook
[book(https://github.com/fm75/jbook-209/pull/new/gh-pages)

+++

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fm75/jbook-209/master?urlpath=lab) master

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fm75/jbook-209/colab_empty?urlpath=lab) colab_empty

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fm75/jbook-209/colab_space?urlpath=lab) colab_space

## master branch - no colab_url
`config.yml` does not specify colab_url.

## colab_empty branch - colab_url no value
`config.yml` colab_url :

## colab_space branch - colab_url ''
`config.yml` colab_url : ''

```{code-cell} ipython3
!jupytext README.ipynb  --to myst
```
