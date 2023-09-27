# Tweaked to work with GraalPy Standalone

This project runs just fine (and fast!) on GraalPy 23.1. This fork includes some tweaks to build standalone binaries that just work with it.
```
graalpy -m standalone native -m pypy-raycaster --venv my-venv-with-pygame-pillow-numpy -o pypy-raycaster.exe
```

Now "pypy-raycaster.exe" includes everything you need to run this demo: on macOS and Linux (Windows coming soon).

# PyPy Raycaster

## Overview
**PyPy Raycaster** is a PyPy implementation of a simple raycasting engine as per [Lode's tutorial](https://lodev.org/cgtutor/raycasting.html).

### Source
<img src="examples/example.gif" alt="screen" width="50%" height="50%">

## Dependencies
* **[PyPy](https://www.pypy.org/download.html)** 3.7+
* **[Pillow](https://pillow.readthedocs.io/en/stable/)** 8.0+
* **[PyGame](https://github.com/pygame/pygame/releases/tag/2.0.0)** 2.0+
* **[NumPy](https://numpy.org/install/)**

