# interactive-jupyter

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/git/https%3A%2F%2Fgithub.com%2Fdj-application%2Finteractive-jupyter/master?filepath=test-pddocs-demo%2Fdocstring_error_interactive.ipynb)

##  How to render live Jupyter notebooks?
```
# 1. Create a conda environment
conda env create
conda activate interactive-jupyter


# 2. Render a notebook as an interactive notebook using voila
# 1) Default: render a notebook as a standalone application without source code
voila voila/notebooks/basics.ipynb

# 2) If you want to show the source code
voila voila/notebooks/basics.ipynb --strip_sources=False


# 3. Open http://localhost:8866/


# 4. Some settings
# 1) update jupyter
conda update jupyter

# 2) qgrid
jupyter nbextension enable --py --sys-prefix qgrid

# 3) as a server extension to notebook or jupyter_server
jupyter serverextension enable voila --sys-prefix

# 4) jupyter nbextensions
jupyter nbextension enable --py widgetsnbextension
```

## How to host a jupyter notebook on Binder?

  * Go to https://mybinder.org/
    * Arbitrary git repository URL `https://github.com/dj-application/interactive-jupyter/ `
    * Path to a notebook file (optional)
    `test-pddocs-demo/docstring_error_interactive.ipynb`
    * Click `Launch`
    * Copy the URL below and share your Binder with others
    `https://mybinder.org/v2/git/https%3A%2F%2Fgithub.com%2Fdj-application%2Finteractive-jupyter/master?filepath=test-pddocs-demo%2Fdocstring_error_interactive.ipynb`


## Reference
 * [binder](https://mybinder.readthedocs.io/en/latest/)
 * [bqplot](https://bqplot.readthedocs.io/en/stable/index.html)
 * [qgrid](https://github.com/quantopian/qgrid)
 * [voila](https://github.com/QuantStack/voila)
 * [voila-gallery](https://voila-gallery.org/services/gallery/)
 * [Jupyter Notebook Extensions](https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231)
 * [Interactive spreadsheets](https://towardsdatascience.com/interactive-spreadsheets-in-jupyter-32ab6ec0f4ff)
 * [Interactive Controls in Jupyter Notebooks](https://towardsdatascience.com/interactive-controls-for-jupyter-notebooks-f5c94829aee6)
