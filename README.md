# regression-from-scratch

demonstrate how to do regression from scratch in python with numpy for PGH Data Science Meetup. 

## requirements

* conda

## setup 

the following step isn't necessary, but is useful for managing / switching kernels when launching
jupyter notebooks from the default environment.

`conda install nb_conda -q --yes`

The following will set up the environment containing the requirements for the notebook.

`conda create --name=pgh_data_science python=3.5 --file=requirements.txt --yes`

which will create the environment for regression from scratch.  to switch to that environment use

`activate pgh_data_science` on windows or `source activate pgh_data_science` on linux
