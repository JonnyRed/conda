# Conda 

## Package management with conda

## Conda references

[User Guide][]

[User Guide]:https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#

## Create environment

`conda env create -f "D:\Users\John\Documents\IPython Notebooks\Sympy\environment.yml"`

## Remove environment

`conda remove --name sympy --all`

## List Packages

List all the revisions and their packages

`conda list --revisions`

List by environment

`conda list -n Riley`

List by environment and package

`conda list pandas -n Riley`

## Admin commands

## info

List configuration in `.condarc`. It is in yml format.

`conda info`
