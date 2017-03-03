
[Conda] [https://conda.io/docs/using/using.html]

## To check for installed version of conda
`conda --version

## To update conda packages
`conda update conda

## To create an environment called /envs/snowflakes with the program biopython
`conda create -n snowflakes biopython

## To activate the environment
`activate snowflakes

## To deactivate
`deactivate 

## second environment
`conda create --name bunnies python=3 astroid babel

## Environments installed
`conda info --envs

## To clone an exact copy of an environment
`conda create --name flowers --clone snowflakes

## to remove an unwanted environment
`conda remove --name flowers --all

## to check for python versions available for install
`conda search --full-name python

## search anaconda
`anaconda search -t conda pydotplus

## searches for any package with the text python
`conda search python 

## install a different python version in a different environment
`conda create --name snakes python=3

## Create a python3.5 environment including django1.10 from anaconda distribution
`conda create -n py35 python=3.5 django=1.10 anaconda

## Create another environment for python2.7
`conda create -n py27 python=2.7 anaconda

## In an environment with python 3.4.2, this command will upgrade to python 3.4.3
`conda update python

## will upgrade from, say python3.4, to another python branch 3.5
`conda install python=3.5

## list available packages
`conda list

## search for a package
`conda search beautifulsoup4

## to install the package in a specific environment
`conda install -n bunnies beautifulsoup4

## to install a package bottleneck from anaconda.org
`conda install --channel https://conda.anaconda.org/pandas bottleneck

## to use pip for installing package named see
`activate bunnies
`pip install see


# to use an environment with flask
`conda create -n webby flask flask-mysql
