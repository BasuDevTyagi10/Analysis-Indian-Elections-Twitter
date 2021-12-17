# ANALYSIS OF INDIAN ELECTIONS USING TWITTER

## Table of Contents  
- [General Info](#general-info)\
- [Technologies](#technologies)\
- [Getting Started](#getting-started)\
- [Authors](#authors)

## General Info
**Project Purpose :** work done for miniproject evaluation GEU Semester-5

## Technologies
The project is created using :
* Python 3.8.8

## Getting Started
Clone the repo on local machine:
```sh
$ git clone https://github.com/BasuDevTyagi10/Analysis-Indian-Elections-Twitter.git
$ cd "Analysis-Indian-Elections-Twitter"
```
### Create a virtual environment (for better control (version control) over the project)
It is better to use Anaconda Navigator ([Anaconda Documentation - Installation](https://docs.anaconda.com/anaconda/install/)) for handling such (and further mentioned) tasks of creating virtual environments, installing packages, IDEs, Applications, etc.
<br>
<br>For performing the mentioned operations manually (without Anaconda) :
<br><br>Install ```virtualenv``` module to create isolated virtual environments.
```sh
$ pip install virtualenv
```
To create a Virtual Environment for Python 2.x do the following
```sh
$ virtualenv myenv
```
For a Python 3 virtual environment type –
```sh
$ python3 -m venv myenv
```
To activate the virtual environment -
<br>On Windows, run:
```sh
$ myenv\Scripts\activate.bat
```

### Installing required packages
The following packages will be required to be installed for running the ```5thSemMiniProject.ipynb``` jupyter notebook:
<br>```jupyterlab```, ```pandas-profiling```, ```pandas```, ```matplotlib```, ```wordcloud```, ```plotly``` and ```textblob```
<br><br>Install the above mentioned packages in your virtual environment using Anaconda, and without it by:
<br>_run the below command after you're in your virtual environment_
```sh
(myenv)$ pip install jupyterlab pandas-profiling pandas matplotlib wordcloud plotly textblob
```

### Run Jupyter Notebook for the Data Analysis
Once installed, launch JupyterLab with:
```sh
(myenv)$ jupyter-lab
```
Open the ```5thSemMiniProject.ipynb``` jupyter notebook and Run All the Cells.

## Authors

-   **Basudev Tyagi** - _Initial work_ - [BasuDevTyagi10](https://github.com/BasuDevTyagi10)
