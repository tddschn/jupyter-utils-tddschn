# jupyter-utils-tddschn

Most code were copied from https://jupyter-notebook.readthedocs.io/en/stable/examples/Notebook/Importing%20Notebooks.html

## How do I ... ?

### Import a `.ipynb` file?

```python
from jupyter_utils_tddschn import notebook_importer

# then just import a .ipynb file like a .py file
# to import test.ipynb:
import test
```

### Show the content of a notebook, syntax highlighted?

```python
from jupyter_utils_tddschn.notebook_shower import show_notebook

show_notebook('notebooks/test.ipynb')

```