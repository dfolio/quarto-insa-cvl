# quarto-insa-cvl Quarto extension

![Tested on Quarto-1.3](https://img.shields.io/badge/quarto-1.3-blue?label=quarto)

## Overview
`insa-cvl` is a personal [Quarto] format for [my teaching](https://dfolio/teaching/)  materials.
Even if the repository is made public, this [Quarto extension](https://quarto.org/docs/extensions/) is not for a general audience.
`quarto-insa-cvl` is developped for my own taste.
However, if you are curious to know how some stuff is made, feel free to send a PR.

## Installing

```bash
quarto use template dfolio/quarto-insa-cvl
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

## Using

To add this format to an existing document:

``` bash
quarto add dfolio/quarto-insa-cvl
```

## Updating

```bash
quarto list extensions
quarto update dfolio/quarto-insa-cvl
```

## Removing

```bash
quarto remove  dfolio/quarto-insa-cvl
quarto list extensions
```

[Quarto]: https://quarto.org/
