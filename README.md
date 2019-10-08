# A fun example of topic modeling using LDA on Gabriel Garcia Marquez's 100 Years of solitude

<img align="left" width="300" src="https://www.goliath.com/wp-content/uploads/2015/11/one-hundred-years-of-solitude-original-imadj8fyvx6gbmgf-730x1108.jpeg">

Run this notebook in a browser by clicking on the button below.

> [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/betolink/scipy-topics/master?filepath=notebooks%2Fgabo-lda.ipynb)  __to launch EGU sessions analysis__

The notebooks can also be executed on your own machine by using docker or in a Conda environment. See below for instructions

### Using Conda environments


```sh
conda env create -f binder/environment.yml
```
now to use the notebooks we need to activate the environment and run jupyter

```sh
source activate topics
jupyter notebook --allow-root --notebook-dir=$MY_DIR --ip='0.0.0.0' --port=8888 --no-browser
```

### LICENSE
[![License: LGPL v3](https://img.shields.io/badge/License-LGPL%20v3-blue.svg)](https://www.gnu.org/licenses/lgpl-3.0)

