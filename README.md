# Machine Learning Jupyter Notebooks

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/theed-ml/notebooks/master) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/theed-ml/notebooks/)
[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)

This repository contains the Jupyter notebooks of the machine learning course. 

## Quick start

You can the notebooks without having to install anything locally. For this, you can use one of the following services.

* Open this repository in [Binder](https://mybinder.org/v2/gh/theed-ml/notebooks/master):
<a href="https://mybinder.org/v2/gh/theed-ml/notebooks/master"><img src="https://matthiasbussonnier.com/posts/img/binder_logo_128x128.png" width="55" /></a>

* Open it in [Deepnote](https://beta.deepnote.com/launch?template=data-science&url=https://mybinder.org/v2/gh/theed-ml/notebooks/master):
<a href="https://beta.deepnote.com/launch?template=data-science&url=https%3A//github.com/theed-ml/handson-ml2/notebooks/master/"><img src="https://www.deepnote.com/static/illustration.png" width="100" /></a>

* Or open it in [Colab](https://colab.research.google.com/github/theed-ml/notebooks/blob/master/):
<a href="https://colab.research.google.com/github/ageron/handson-ml2/blob/master/"><img src="https://colab.research.google.com/img/colab_favicon.ico" width="50" /></a>

If you only want to view some notebook without executing any code, you can use:

* [Jupyter notebook viewer](http://nbviewer.jupyter.org/github/theed-ml/notebooks/):
<a href="http://nbviewer.jupyter.org/github/theed-ml/notebooks"><img src="https://jupyter.org/assets/nav_logo.svg" width="80" /></a>
* [GitHub notebook viewer](https://github.com/theed-ml/handson-ml2/): <a href="http://nbviewer.jupyter.org/github/theed-ml/notebooks"><img src="https://github.blog/wp-content/uploads/2013/04/fffdd290-a5e2-11e2-8099-e1b5d8286da3.jpg" width="80" /></a>


## Running the notebooks locally

If you have a Python 3.6+ environment, then this project can be cloned and its dependencies installed locally through pip. In this case, open a terminal and run the following commands:

```sh
git clone https://github.com/theed-ml/notebooks.git && cd notebooks
python3 -m pip install --user --upgrade pip setuptools    
python3 -m pip install --user --upgrade -r requirements.txt
jupyter notebook
```

