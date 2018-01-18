# `nb_extensions_ipy_magics`

Meta-repository for collating innovationOUtside `nb_extensions` and `ipython_magics`.

Will also include generic howtos for creating Jupyter notebooks and IPython magics.

## `nb_extensions`


### Extensions

- [`nb_extension_wordexport`](https://github.com/innovationOUtside/nb_extension_wordexport): export notebook to Microsoft Word document
- [`nb_extension_odszip`](https://github.com/innovationOUtside/nb_extension_odszip): save notebook `.ipynb` and `.html` versions in a zip file with *.ods* suffix.



### Creating an installation package from files in a local direcoty

Create zip file for pip install"

- `cd MY_EXTENSION_DIR; zip -r MY_EXTENSION.zip ./*`

Note: this may zip unwanted hidden files.

Install from zipfile:

`!pip3 install --upgrade --force-reinstall /PATH/TO/MY_EXTENSION.zip`

## `ipython_magics`

- [ipython_magic_tikz](https://github.com/innovationOUtside/ipython_magic_tikz): IPython magic for rendering *TikZ* generated images
- [ipython_magic_asymptote](https://github.com/innovationOUtside/ipython_magic_asymptote): IPython magic for rendering *asymptote* generated images
