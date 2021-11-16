# Topic modeling using LDA
The goal of this work is to identify consistent topics in time, i.e., set of terms that become frequent together throughout time.
# Data set 
 Twitter dataset on COVID-19 from Kaggle (https://www.kaggle.com/gpreda/covid19-tweets).

### Project notebooks
 
There are two notebooks for this project. 
1. Data processing.ipynb => This notebook contains an implementation of data preprocesing. It was used to create processed data which eventually will be used by the LDA topic modeling algorithm
2. Topic Modeling.ipynb => This notebook contains an implementation of the LDA algorithm for topic modeling and the visualization of the experimental results


>> In order to run the notebooks jupyter notebook should be installed and pip should be registered in the environment variables. This can be confirmed by running the following code on command line interface(cmd/terminal).

```bash
pip --version
```
The above snipt of code will show information about pip. If pip is not installed or not registered in the envirnoment variable it will show error. If there is no error means pip can be accessed from the command line interface.

If pip is not installed on the environment [this link](https://pip.pypa.io/en/stable/installing/) have a great resource for pip installation.



```bash
jupyter --version
```
This code will show information related to jupyter including the version and some related libraries installed. If you get an error it means the jupyter is not installed or cannot be accessed from the command line inteface.

If Jupter is not installed on a machine [this link](https://jupyter.readthedocs.io/en/latest/install.html) have information in different options to install a jupter on a machine.



## Running Project noteooks

Once the pip and jupyter notebook have been installed and can be accessed from the command line interface, the notebooks can be started using jupyter. There are different ways to run the notebook. Here simpler way have been presented.

* Step 1: Change the working directory of the project to the project folder
* Step 2: run the following command on the cmd
```bash
jupyter notebook
```
* Step 3: A browser will pop up with a notebook. If the browser is not press a link on the cmd which has "htts://localhost:" in it. This will open a notebook on a browser.
* Step 4: Now each cell can be run by pressing "SHiFT + ENTER" on your machine

