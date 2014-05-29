# ICWSM '14 Online Experiments for Computational Social Science Tutorial
Welcome to the PyData '14 Silicon Valley PlanOut tutorial! You'll find a collection of IPython notebooks for Eytan Bakshy's tutorial on PlanOut.


## Requirements
### Software requirements
The tutorial requires IPython, Pandas, and PlanOut. The former two come with Anaconda. PlanOut has only been tested on Mac OS X and Linux.

 * IPython ([installation instructions](http://ipython.org/install.html). We recommend Anaconda.)
 * PlanOut v0.2 or greater (first timers `pip install planout`, older timers `sudo easy_install --upgrade planout`)
 * R

Note that you may need to re-install the `planout` package if you installed PlanOut before installing IPython.

### Downloading the tutorial files
If you have git, you can checkout PlanOut by typing:

```
git clone https://github.com/facebook/planout.git
```

or you can [click here](https://github.com/facebook/planout/archive/master.zip) to download a zip archive.


## Loading up the tutorial notebooks
Navigate to your checked out version of PlanOut and type:

```
cd contrib/icwsm14_tutorial/
ipython notebook --pylab inline
```

Tutorial files include:
 * `0-getting-started.ipynb`: This teaches you the basics of how to implement experiments in pure Python.
