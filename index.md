---
title: "Complete Example of Tutorial in Pandoc Markdown"
author:
  - name:
      given: Raniere Gaia
      family: Costa da Silva
    email: Raniere.CostadaSilva@gesis.org
    orcid: 0000-0002-8381-3749
    attributes:
      corresponding: true
    affiliations:
      - name: GESIS Leibniz Institute for the Social Sciences
        department: Computational Social Science
        team: Transparent Social Analytics
        url: https://www.gesis.org
  - name:
      given: David
      family: Schoch
    orcid: 0000-0003-2952-4812
    affiliations:
      - name: GESIS Leibniz Institute for the Social Sciences
        department: Computational Social Science
        team: Transparent Social Analytics
        url: https://www.gesis.org
image: img/cover.jpg
image-alt: Hands typing in a typemachine.
bibliography: references.bib
---

This example illustrates the **required** metadata by [`andrew`](https://github.com/GESIS-Methods-Hub/andrew) for a tutorial written as a Pandoc Markdown, an extension to Markdown [@markdown2004]. The metadata uses Quarto's [Author Schema](https://quarto.org/docs/journals/authors.html#author-schema) and [Affiliations Schema](https://quarto.org/docs/journals/authors.html#affiliations-schema).

GitHub renders `.md` files as [GitHub Flavored Markdown](https://github.github.com/gfm/) and, because of it, some elements will not be correct display on GitHub. Images and Tables should be correct display on GitHub.

![Photo of weathercock by Mat Brown. Available at <https://www.pexels.com/photo/silhouette-of-wind-vane-552600/>.](img/north.jpg){#fig-north}

| Vowel | Frequency in English |
|---|---|
| a | 8.17% |
| e | 12.70% |
| i | 6.97% |
| o | 7.51% |
| u | 2.76% |

: List of vowels and frequencies {#tbl-vowel}

Although footnotes are supported, the use of footnotes is discouraged[^1].

[^1]: Because of it makes navigation harder.

Math can be written using [LaTeX](https://www.latex-project.org/) and is render by [MathJax](https://www.mathjax.org/). Both inline, for example $x$, and display, for example $$x = \sqrt{a^2 + b^2}\text{,}$$ is supported.

## Binder

The link to Binder will launch the default [JupyterLab IDE](https://jupyterlab.readthedocs.io/).

## References

::: {#refs}
:::