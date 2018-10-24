# Pandas-Workshop-Uni-Stuttgart

Learn how Pandas works in Python (3) in Jupyter Notebook with additionally some Matplotlib examples.

---
**Simple setup instructions**:

1. Install [Python 3.\*](https://www.python.org/downloads/) (Latest version is the best option)
2. Install Pandas, Jupyter Notebooks, Matplotlib: `pip install jupyter pandas matplotlib` (or `pip3` instead of `pip`)
3. Clone this repository: `git clone https://github.com/AnonymerNiklasistanonym/Pandas-Workshop-Uni-Stuttgart.git`
4. Start Jupyter Notebook: `jupyter notebook`
5. Wait until a browser window opens and select then in the directory list the cloned directory and open the `*.ipynb` files that you want to open

---

## Setup

### Python 3, Jupyter Notebook

#### Windows

##### Simple installation

- Download [WinPython](https://winpython.github.io/) with QT5 (currently version 3.5.4)
- Extract the contents into a directory, you can find in this directory all needed executables

##### Normal installation

- Install the current version of [Python 3](https://www.python.org/downloads/windows/)
- Then enter in the console the following:

```bash
pip install jupyter # or use pip3 if you have mapped it to python3
pip install pandas
pip install matplotlib
```

#### OSX

- Install the current version of Python 3 via Homebrew
- Then install Jupyter via pip3 (Tutorial: https://gist.github.com/NickRSearcy/c46771d83a3168481eee)

#### Linux

- Install Python 3 and Jupyter Notebook via your package manager of your distribution

### Pandas und Matplotlib

#### Windows

Already everything installed through WinPython

#### OSX/Linux

- Install pandas via pip3 und matplotlib via Homebrew or respectively your package manager

### Check if everything works

Check if everything is correctly installed by executing Jupyter Notebook and either opening the notebooks of this repository or creating a new notebook and inserting the two lines:

```python
import pandas as pd
import matplotlib.pyplot as plt
```

And then run the notebook/cell ([Shift] + [Enter]).

If no error comes up everything worked.

#### Windows

Double click/execute `Jupyter Notebook.exe` in the extracted directory.

#### OSX/Linux

Enter `jupyter notebook` in your terminal.
