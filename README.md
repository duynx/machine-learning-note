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

<pre name="7b81" id="7b81" class="graf graf--pre graf-after--p"><strong class="markup--strong markup--pre-strong"># update conda in your default environment </strong><br><em class="markup--em markup--pre-em">$ </em><code class="markup--code markup--pre-code"><em class="markup--em markup--pre-em">conda upgrade conda<br>$ conda upgrade --all</em></code></pre>
