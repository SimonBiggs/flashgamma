# flashgamma

A python package for speedy analyses of 2D radiotherapy dose distributions.

## Installation

Installation is through `pip`. You must have `numpy` installed in your environment first. You may also wish to install matplotlib to run the examples.

    pip install numpy matplotlib
    pip install flashgamma

## Examples

Checkout the examples folder for details.

**Example 1** demonstrates how to perform a gamma analysis on some ArcCheck data:

![](./examples/images/eg1.png)

**Example 2** uses arbitrary `numpy` arrays:

![](./examples/images/eg2.png)

**Example 3** uses a `cython` based function to rapidly calculate gamma pass rates. That means you can analyse entire ranges of dose difference and distance to agreement criteria at once, generating interesting plots like this:

![](./examples/images/eg3.png)

## Caveats

This code was written for personal educational purposes. Although it was shown internally to perform similarly to a range of proprietary gamma analysis codes, it is in no way guaranteed to be free from bugs and errors.

## Literature

This software was featured in the following publication:

Samuel C. Peet, Liting Yu, Sarah Maxwell, Scott B. Crowe, Jamie V. Trapp, Tanya Kairn. (2020). "Exploring the gamma surface: A new method for visualising modulated radiotherapy quality assurance results". Physica Medica: European Journal of Medical Physics, Volume 78, 166-172. (https://doi.org/10.1016/j.ejmp.2020.09.021)
