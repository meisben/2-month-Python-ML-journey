# SciPy2018 tutorial: Introduction to Numerical Computing with NumPy

#### Presented by: Alexandre Chabot-Leclerc, [Enthought Inc.](https://www.enthought.com)

This repository contains all the material needed by students registered for the Numpy tutorial of SciPy 2018 on Monday, July 9th 2018.

For a smooth experience, you will need to make sure that you install or update your Python distribution and download the tutorial material _before_ the day of the tutorial as the Wi-Fi at the AT&T center can be flaky.

## Install Python

If you don't already have a working python distribution, you may download Enthought Canopy ([https://store.enthought.com/downloads](https://store.enthought.com/downloads)), Anaconda Python ([https://www.anaconda.com/download/](https://www.anaconda.com/download/)) or Python.org ([https://www.python.org/downloads/](https://www.python.org/downloads/)).


## Install Packages

To be able to run the examples, demoes and exercises, you must have the
following packages installed:

- numpy 1.13+
- matplotlib 2.0+
- ipython 5.0+ (for running, experimenting and doing exercises)

With Canopy, the required packages are already installed. If you are using Python from python.org or your system, you can install the necessary packages with:

```sh
$ pip install -U numpy matplotlib ipython
```

If you are using Anaconda, you can install the necessary packages with:

```sh
$ conda install numpy matplotlib ipython
```

To test your installation, please execute the `check_env.py` script.

```sh
$ python check_env.py
```

You should see a window pop up with a plot that looks vaguely like a smiley face.

## Download Tutorial Materials

This GitHub repository is all that is needed in terms of tutorial content. The simplest solution is to download the material using this link:

https://github.com/enthought/Numpy-Tutorial-SciPyConf-2018/archive/master.zip

If you're familiar with Git, you can also clone this repository with:

```sh
$ git clone https://github.com/enthought/Numpy-Tutorial-SciPyConf-2018.git
```

It will create a new folder named `Numpy-Tutorial-SciPyConf-2018/` with all the content you will need: the slides I will go through (`slides.pdf`), and a folder of exercises.


## Questions? Problems?

You may post messages to the slack channel for this tutorial at: [https://scipy2018.slack.com](https://scipy2018.slack.com) (The channel doesn't yet exist as of 2018-06-10, but it should soon.)
