# UKRI Cloud Workshop Demo

This repo demonstrates how versions of Python packages can introduce significant changes to the execution of code that don't necessarily fail.

The upgrade of Matplotlib from version 1.x to 2.x changed the colour maps of the library.

To launch the notebook with Matplotlib v1.5.0: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sgibson91/ukri_demo/mpl-v1.5/?filepath=demo.ipynb)

To launch the notebook with Matplotlib v2.0.0: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/sgibson91/ukri_demo/mpl-v2.0/?filepath=demo.ipynb)

NOTE: Each version of Matplotlib has its own Numpy dependency which are different in this scenario.
