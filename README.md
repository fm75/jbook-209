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
colab defaults on in jbook?

- [generated book](https://fm75.github.io/jbook-209/README.html)
- The colab dropdown does not appear in any of these experiments (branches).

+++

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fm75/jbook-209/master?urlpath=lab) master

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fm75/jbook-209/colab_empty?urlpath=lab) colab_empty

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/fm75/jbook-209/colab_space?urlpath=lab) colab_space

## master branch - no colab_url
`config.yml` does not specify colab_url.

## colab_empty branch - colab_url no value
`config.yml` colab_url :

This is not valid yaml. `make build` warns
```bash
Warning: Validation errors in config:
- None is not of type 'string' [key path: 'launch_buttons/colab_url']
```

## colab_space branch - colab_url ''
`config.yml` colab_url : ''

```{code-cell} ipython3
!jupytext README.ipynb  --to myst
```
