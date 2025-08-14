# Compress, Compute, and Conquer: Python-Blosc2 for Efficient Data Analysis (EuroSciPy 2025 tutorial)

Here you will find materials for the ironArray SLU tutorial on Python-Blosc2 for EuroSciPy 2025 in Krakow, Poland.

## Preliminaries
Before the tutorial, it is advisable to have jupyter notebook installed (see [here](https://jupyter.org/install)).
This can be managed via Anaconda if you prefer (download [here](https://www.anaconda.com/download) and follow the instructions), 
but in the command line (Windows/Linux/MacOS) it is very simple.

Before installing Jupyter Notebook, make sure you have Python (version 3.8 or later) installed and either ``conda`` 
or ``pip`` 
```
python --version
pip --version
conda --version
```
``conda`` may be installed via following the instructions here https://docs.conda.io/en/latest/miniconda.html.

### Installing Jupyter Notebook
Install Jupyter using ``pip`` via
```pip install notebook```
or ``conda`` via
```conda install -c conda-forge notebook```
(make sure you are in the desired environment using ``conda activate myenv`` of course).

#### Opening Jupyter Notebook from the Command Line
Once installed, you can launch Jupyter Notebook by running
```jupyter notebook```
which will open a window in your browser, where you may manage notebooks.

### Clone this git repo
Use either SSH, url or a zip file (click on the green 'Code' button in the top right), making sure to clone into the relevant directory. 
One may navigate to the repo via the command line, or from the jupyter notebook web browser interface.

### Install dependencies
From the command line run either
```
pip install caterva2[services]==2025.8.7 psutils blosc2==3.7.0 matplotlib ipympl
```
or 
```
conda install -c conda-forge caterva2[services]==2025.8.7 psutils python-blosc2=3.7.0 matplotlib ipympl
```
Alternatively, in a jupyter notebook cell, run (note the exclamation mark).
```
!pip install caterva2[services]==2025.8.7 psutils blosc2==3.7.0 matplotlib ipympl
```

That should be it! Open the first notebook and check that the first few cells all run to be sure!
