# quantum-simulator
1-Dimensional Toy Simulation of the Schrodinger Equation.

![Screenshot of main window.](https://raw.githubusercontent.com/wgxli/quantum-simulator/master/screenshot.png)

## Usage
Simply run `main.py`.

## Features
* Stable simulation of unitary evolution.
* Stable time acceleration.
* View evolution of wavefunction in different bases.
* Measure observables and simulate the collapse of the wavefunction.

## Requirements
Currently supports only Python 3.
Requires the following libraries:
* PyQt5
* Numpy
* Scipy
* pyqtgraph

## Limitations
* Does not yet support time-varying potentials.
* Currently supports only one dimensional wavefunctions.
* Components with very high energy are discarded to improve numerical stability.
