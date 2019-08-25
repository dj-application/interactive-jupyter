# interactive-jupyter

##  How to add interactive controls in jupyter notebooks?
```
# 1. Create a conda environment
conda env create
conda activate interactive-jupyter

# 2. Render a notebook as an interactive notebook using voila

# 1) Default: Render a notebook as a standalone application without source code 
voila notebook.ipynb

# 2) However, if you want to show the source code for a voila notebook
voila basics.ipynb --strip_sources=False

# 3. Open http://localhost:8866/
```


## Reference
 * [binder](https://mybinder.org/v2/gh/WillKoehrsen/Data-Analysis/widgets-stable?filepath=widgets%2FWidgets-Overview.ipynb)
 * [bqplot](https://github.com/bloomberg/bqplot)
 * [Voila](https://github.com/QuantStack/voila)
 * [voila-gallery](https://voila-gallery.org/services/gallery/)
 * [Interactive Controls in Jupyter Notebooks](https://towardsdatascience.com/interactive-controls-for-jupyter-notebooks-f5c94829aee6)
 * [Jupyter Notebook Extensions](https://towardsdatascience.com/jupyter-notebook-extensions-517fa69d2231)
