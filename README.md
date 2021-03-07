# Conda Windows Environment

## After installing miniconda
`cd Desktop`

`mkdir sample_project`

`cd sample_project`

`conda create --prefix ./env pandas numpy matplotlib scikit-learn`

`conda activate C:\Users\MSI\Desktop\env`

>To add extra software to current env
 
`conda install jupyter`

> Conda Environment list

`conda env list`

> Conda package list

`conda list`

> Conda search all version of a package

`conda search ipython --info`

> Conda Uninstall package

`conda uninstall scikit-learn python`

> Conda install package with specifig version

`conda install packages 3.6.9 scikit-learn=0.22 matplotlib pandas jupyter `