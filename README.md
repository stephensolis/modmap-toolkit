# modmap-toolkit

[![Build Status](https://travis-ci.org/stephensolis/modmap-toolkit.svg?branch=master)](https://travis-ci.org/stephensolis/modmap-toolkit)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/2286db6fde1d4b729127f820d7896cd0)](https://www.codacy.com/app/stephensolis/modmap-toolkit)
[![PyPI version](https://badge.fury.io/py/modmap-toolkit.svg)](https://badge.fury.io/py/modmap-toolkit)

This is a fast and user-friendly generation and analysis pipeline for Molecular Distance Maps.

It uses:

- [stephensolis/modmap-generator-cpp](https://github.com/stephensolis/modmap-generator-cpp) to generate kmer count vectors and distance matrices
- [scikit-learn](http://scikit-learn.org/) for supervised classifiers
- [Wolfram Mathematica](https://www.wolfram.com/mathematica/) and code based on [stephensolis/modmap-generator-mma](https://github.com/stephensolis/modmap-generator-mma) to generate interactive plots
- [NumPy](http://www.numpy.org/) and [SciPy](https://www.scipy.org/) for MultiDimensional Scaling (MDS)

## License ![License](http://img.shields.io/:license-mit-blue.svg)

    The MIT License (MIT)

    Copyright (c) 2017 Stephen

    Permission is hereby granted, free of charge, to any person obtaining a copy
    of this software and associated documentation files (the "Software"), to deal
    in the Software without restriction, including without limitation the rights
    to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
    copies of the Software, and to permit persons to whom the Software is
    furnished to do so, subject to the following conditions:

    The above copyright notice and this permission notice shall be included in all
    copies or substantial portions of the Software.

    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
    IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
    FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
    AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
    LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
    OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
    SOFTWARE.
