# Simple-functions-for-starting-machine-learning-with-Python
<p align="justify">The current repository contains different notebooks, in which functions are implemented in Python from scratch, to understand the basic steps to carry out a machine learning problem.</p>

## Getting Started

<p align="justify">These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.</p>

### Prerequisites

<p align="justify">You need Python 3.x to run the following code.  You can have multiple Python versions (2.x and 3.x) installed on the same system without problems.</p>

In Ubuntu, Mint and Debian you can install Python 3 like this:

    sudo apt-get install python3 python3-pip

The Jupyter Notebook which can be installed through Python's package manager:

    pip3 install --upgrade pip
    pip3 install jupyter

For other Linux flavors, OS X and Windows: 

Python is available at http://www.python.org/getit/    
Jupyter Notebook at https://jupyter.readthedocs.io/en/latest/install.html


## File descriptions
<ul>
    <li>The files "<em>iris.csv</em>" and "<em>winequality-white.csv</em>" which correspond to the 2 datasets used in the different notebooks.</li>
    
<li><div align="justify">"<em>Open_conversion_data.ipynb</em>" is the first Jupyter notebook of the series, which treats of the initial operations to be done to read the data from a CSV file, modify the variable types in the different columns (features) of the dataset, as well as data re-scaling, such as normalization and standardization.</div></li>
    
<li><div align="justify">"<em>Split_dataset.ipynb</em>" is the second Jupyter notebook of the series, where 2 approaches to split a dataset are implemented, to understand how the split between training and testing occur for machine learning problems.</div></li>

<li><div align="justify">"<em>Performance_assessment.ipynb</em>" is the third Jupyter notebook of the series in which, accuracy metrics to measure machine learning algorithms performance are introduced, and implemented in a simple way.</div></li>
</ul>

### Running the files

<p align="justify">The notebooks can be <b>directly opened on GitHub</b>. An alternative way to open the notebooks, is to run the Jupyter Notebook. This can be done by executing the following command at the Terminal (Mac/Linux) or Command Prompt (Windows):</p>

    jupyter notebook

<p align="justify">This will print some information about the notebook server in your terminal, including the URL of the web application (by default, http://localhost:8888):</p>

    $ jupyter notebook
    [I 11:47:00.830 NotebookApp] Serving notebooks from local directory: C:\Users\EC-PM-3
    [I 11:47:00.830 NotebookApp] The Jupyter Notebook is running at:
    [I 11:47:00.830 NotebookApp] http://localhost:8888/?token=d22181d47f4826316a37161bb8c8469d77a5851bf9ab2c1f
    [I 11:47:00.830 NotebookApp] Use Control-C to stop this server and shut down all kernels (twice to skip confirmation).

It will then open your default web browser to this URL.

<p align="justify">When the notebook opens in your browser, you will see the Notebook Dashboard, which will show a list of the notebooks, files, and subdirectories in the directory where the notebook server was started. The notebook can then be chosen by navigating in the Notebook Dashboard.</p>

For more information on how to run a specific jupyter notebook, you can go to the <a href="https://jupyter.readthedocs.io/en/latest/running.html#running">following link</a>.

## Contributing

Please read [CONTRIBUTING.md](https://github.com/DavidCico/Simple-functions-for-starting-machine-learning-with-Python/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **David Cicoria** - *Initial work* - [DavidCico](https://github.com/DavidCico)

See also the list of [contributors](https://github.com/DavidCico/Simple-functions-for-starting-machine-learning-with-Python/graphs/contributors) who participated in this project.
