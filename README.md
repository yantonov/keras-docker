Scripts are aimed to simplify using keras (with cpu support) through docker image.

Docker directory contains scripts to build, run, get terminal access, remove constructed image.

Usage:
Add 'cpu' repository to PATH and use dl.sh.
Current directory will be mounted automatically.

Docker file provides:
1. [python](https://www.python.org/download/releases/3.0/) 3.8
2. [tensorflow](https://www.tensorflow.org) 2.3.0
3. [keras](https://github.com/keras-team/keras)
4. [anaconda](https://anaconda.org/anaconda/python) 2020.07
5. [jupiter](http://jupyter.org/)

Links:
[hub.docker.com](https://hub.docker.com/r/yantonov/dl-cpu)
