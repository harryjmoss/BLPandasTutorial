# BL/QFP Code Club Pandas tutorial - slides and notebooks
[![Link to notebooks on Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/harryjmoss/BLPandasTutorial/master)

## How to use this repository
The notebooks contained in this repository can either be run locally on your own computer or through [Binder](https://mybinder.org/), where they are hosted remotely and can be run by any user with no pre-installation required. 

#### To run remotely through Binder 
Click the 'launch binder' link at the top of this README - this may take a while to load but avoids any installation described below!

#### To run locally
*These instructions are also provided in slides/PandasOverview_notebook.ipynb*

*The following commands should be entered in a terminal of your choice!*  

Ensure you have Python 3.X installed and create a virtual environment, where `$envname` is any name you would like (without a dollar sign!)
```
python -m venv $envname
```
Activate your environment

**Linux/macOS**
```
sh $envname/bin/activate
```

**Windows**
```
sh $envname/Scripts/activate
```
Install any Python packages necessary
```
pip install -r requirements.txt
```
Launch jupyter notebooks (launches a graphical file explorer similar to windows - then just find the notebook you want to run!)
```
jupyter notebook
```

### Slides
Presentation slides can be found in [slides](slides/)

### Notebook
An interactive Jupyter notebook version of the slides shown on 15/06/2020 is provided in [slides/PandasOverview_notebook.ipynb](slides/PandasOverview_notebook.ipynb)

### Bokeh tutorial
A very brief runthrough of a Programming Historian data visualisation tutorial is included as an optional extra(!) within [notebooks/ProgrammingHistorian_BokehTutorial.ipynb](notebooks/ProgrammingHistorian_BokehTutorial.ipynb)

### Included  data
Example spreadsheets are provided in the `data` directory as `.csv` and `.xlsx` formats and are referred to in the tutorial notebooks. You shouldn't need to add anything here, but feel free to add your own datasets in and try out some pandas features!


