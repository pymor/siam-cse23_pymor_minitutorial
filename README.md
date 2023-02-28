# SIAM CSE23 pyMOR Minitutorial

## Running Online (Binder)

- Run on [mybinder.org](https://mybinder.org) infrastructure:&nbsp;&nbsp; [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/pymor/siam-cse23_pymor_minitutorial/HEAD?filepath=content)
- Run on [Uni Münster](https://www.uni-muenster.de) infrastructure:&nbsp;&nbsp; [![Binder](https://mybinder.org/badge_logo.svg)](https://binderhub.uni-muenster.de/v2/gh/pymor/siam-cse23_pymor_minitutorial/HEAD?filepath=content&token=c35b1d33ae482736)

## Running Locally (JupyterLite)

- Run as WebAssembly in your browser using [JupyterLite](https://jupyterlite.readthedocs.io):&nbsp;&nbsp;[![JupyterLite](https://jupyterlite.readthedocs.io/en/latest/_static/badge.svg)](https://pymor.github.io/siam-cse23_pymor_minitutorial)

## Running Locally (Linux)

Tested on Python 3.8

    python -m venv .venv
    source .venv/bin/activate
    pip install -U pip setuptools wheel
    pip install -r requirements.txt
    pip install -r dev-requirements.txt
    jupyter-lab


## Running in an existing jupyter environment

    pip install git+https://github.com/pymor/pymor@siam-cse23
