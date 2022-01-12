# voila-retro

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/martinRenou/voila-retro/master?urlpath=voila/render/gradient_descent.ipynb)

Retrolab design template for voila and nbconvert

## Installation

With conda/mamba:

```bash
conda install -c conda-forge voila-retro

# Or faster
mamba install -c conda-forge voila-retro
```

With pip:

```bash
pip install voila-retro
```

## Usage

With [voila](https://github.com/voila-dashboards/voila):

```
voila my_notebook.ipynb --template=retro

# Or with the dark theme:
voila my_notebook.ipynb --template=retro --theme=dark
```

With [nbconvert](https://github.com/jupyter/nbconvert):

```
jupyter nbconvert --to html --HTMLExporter.template_name=retro my_notebook.ipynb

# Or with the dark theme:
jupyter nbconvert --to html --HTMLExporter.theme=dark --HTMLExporter.template_name=retro my_notebook.ipynb
```

### Light theme

![screenshot](./images/retro-light.png)

### Dark theme

![screenshot](./images/retro-dark.png)
