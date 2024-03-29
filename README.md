# ML_Example
This repository contains a machine learning example in python along with environment configuration data.` The Jupyter notebook, dataset (<a href="https://archive.ics.uci.edu/ml/datasets/Iris/" target="_blank">the Iris dataset from UCI</a>), and configuration files are included.

You need to install <a href="https://www.anaconda.com/download/" target="_blank">anaconda</a> on either OSX or Linux.  Running Ubutu on the Windows 10 Linuxsubsystem works just as well. I've done this on Windows 10 running bash (Ubuntu Linux)..

From a bash terminal create the environment you will need:

```
    conda env create -f environment.yml
```


If all goes well you should now have a properly configured python environment called py3.  Then activate the environment:
    
```
     conda activate py3
```


Then fire up the notebook:


```
     jupyter notebook --ip=127.0.0.1
```


EIther a browser will open with Jupyter running, or you will see, from the command line, the URL to use to access Jupyter.  
