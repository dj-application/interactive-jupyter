# interactive-jupyter

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
```
```
# Some settings
# update jupyter
conda update jupyter

# qgrid
jupyter nbextension enable --py --sys-prefix qgrid

# As a server extension to notebook or jupyter_server
jupyter serverextension enable voila --sys-prefix

```

## Reference
 * [binder](https://mybinder.org/v2/gh/WillKoehrsen/Data-Analysis/widgets-stable?filepath=widgets%2FWidgets-Overview.ipynb)
 * [bqplot](https://bqplot.readthedocs.io/en/stable/index.html)
 * [qgrid](https://github.com/quantopian/qgrid)
 * [voila](https://github.com/QuantStack/voila)
 * [voila-gallery](https://voila-gallery.org/services/gallery/)
 * [Jupyter Notebook Extensions](https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231)
 * [Interactive spreadsheets](https://towardsdatascience.com/interactive-spreadsheets-in-jupyter-32ab6ec0f4ff)
 * [Interactive Controls in Jupyter Notebooks](https://towardsdatascience.com/interactive-controls-for-jupyter-notebooks-f5c94829aee6)
