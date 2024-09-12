# nc.mplstyle

[![Python 3.12](https://img.shields.io/badge/python-3.12-blue.svg)](https://www.python.org/downloads/release/python-312/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

Another newcomer in the mplstyle world targeting for scientific plots.

## Requirements

- Need matplotlib (tested on 3.8+)

## Installation

copy the `nc.mplstyle` file to the `mpl_configdir/stylelib` directory. The `mpl_configdir` can be found by running the following code in python:

```python
import matplotlib
print(matplotlib.get_configdir())
```
For details, refer here: https://matplotlib.org/stable/tutorials/introductory/customizing.html

## Usage

```python
import matplotlib.pyplot as plt
plt.style.use('ncxy.mplstyle')
```

## What is the difference betwen ncxy and ncff?

'ncxy' makes only the bottom and left spines visible, while 'ncff' makes all spines visible.
