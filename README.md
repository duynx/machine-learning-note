# machine-learning-note
## Install tensorflow macos
### Required
homebrew, python, pip, virtualenv

<code>python3 -m pip install --upgrade https://storage.googleapis.com/tensorflow/mac/cpu/tensorflow-1.12.0-py3-none-any.whl </code>
## Create virtual env
### Create
<code>virtualenv --system-site-packages -p python3 ./venv
</code>
### Active env
<code>source ./venv/bin/activate</code>
### Exit env
<code>deactivate</code>

References : [https://www.tensorflow.org/install/pip?lang=python3]

## Create Virtual env from anaconda

<code>
# update conda in your default environment  <br>
$ conda upgrade conda <br>
$ conda upgrade --all <br>
# create a new environment with conda <br>
$ conda create -n [my-env-name] <br>
# activate the environment you created <br>
$ source activate [my-env-name] <br>
# take a look at the environment you created <br>
$ conda info <br>
$ conda list <br>
# install a package with conda and verify it's installed <br>
$ conda install numpy <br>
$ conda list <br>
# take a look at the list of environments you currently have <br>
$ conda info -e <br>
# remove an environment <br>
$ conda env remove --name [my-env-name] <br>
</code>
