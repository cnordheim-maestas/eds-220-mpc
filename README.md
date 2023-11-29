# eds-220-mpc
working with microsoft planetary computer

## Caitlin's notes on the python environment:

## *What to do/type in my local terminal:*

navigate to the folder with my repo on my local computer (cd pathname)

"ls" to see what's in there

"conda env list" see all environments installed

"conda create--name test-env python" make a test environment, yes to proceed

"conda activate test-env" to activate it

"conda list" to check package

"conda list pip" to see what version of pip I have

"conda list numpy" to see if we have numpy

### install latest version
"conda install -c conda-forge numpy" installing numpy from forge, yes process

"conda list numpy" to see the version I have

### coding in terminal
"python" to code in python in my terminal

"import numpy as np" to show that you can work in python in the terminal

"quit()" to quit the python interpreter

### delete env
"conda deactivate" to deactivate my test environment

"conda remove --name test-env --all" delete my test environment

Note- this is the pathname to my environments on my local computer: /Users/caitlinnordheim/anaconda3/envs

#### install specific versions
"conda create --name my-numpy-env python=3.9.13 numpy=1.21.5 --channel conda-forge"create env with these specific versions (same as tsosie)

"conda activate my-numpy-env"
"conda list numpy" to see what version we have
"conda list" to see the packages and dependencies in my env
"conda env export > environment_ex.yml" export the environment as a yml
less environment_ex.yml to see it
*press q to exit!!!*

conda env export --from-history --file environment_ex.yml
"less environment_ex.yml" to see it

"rm environment_ex.yml"
"conda deactivate"
"conda remove --name my-numpy-env --all" and yes proceed

#### install env from yml given to you
less environment.yml to see the environment Carmen gave us
note the versions are from the planetary computer and that the planetary computer and pystac client needed to be installed through pip
*press q to exit!!!*

"conda env create --name mpc-env -f environment.yml" creating an environment names mpc-env and it is taking all of the specifications from the environment.yml

will need to create a kernel associated with your environment




