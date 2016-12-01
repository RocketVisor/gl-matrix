glMatrix
=======================
[![Build Status](https://travis-ci.org/toji/gl-matrix.svg)](https://travis-ci.org/toji/gl-matrix)

Javascript has evolved into a language capable of handling realtime 3D graphics,
via WebGL, and computationally intensive tasks such as physics simulations.
These types of applications demand high performance vector and matrix math,
which is something that Javascript doesn't provide by default.
glMatrix to the rescue!

glMatrix is designed to perform vector and matrix operations stupidly fast! By
hand-tuning each function for maximum performance and encouraging efficient
usage patterns through API conventions, glMatrix will help you get the most out
of your browsers Javascript engine.

Learn More
----------------------
For documentation, news, tutorials, and more visit the [glMatrix Homepage](http://glmatrix.net/)

Contributing
----------------------
Contributions are welcome! Please provide unit tests for new functionality.

Running the test suite
----------------------

The unit tests are built upon the following tools:

* Jasmine -- the underlying test suite which executes the test and reports feedback
* node.js -- used for testing at the command line, via the `jasmine-node` package

To run the unit tests run the following command:

    npm run test

Building for the browser
----------------------

To build `gl-matrix.js` and `gl-matrix-min.js` for use in the browser install
the required NPM dependencies first by running

    npm install

from the this directory, then run the following command:

    npm run build-all

This will build the full and minified versions of glMatrix as well as the docs.
