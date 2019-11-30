# Tutorial

## Description

This repository consist of my tutorial on computational physics.

## Convert from .ipynb to HTML

1. Make sure to install Weave package

`] add weave`

2. convert first to ipynb to markdown

`jupyter nbconvert --to markdown <filename>.ipynb`

3. rename the output markdown from *.md to *.jmd

4. open julia REPL in notebook directory, and run this

```
using Weave

weave("<filename>.jmd")
```
