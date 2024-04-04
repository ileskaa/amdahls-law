Notebook to illustrate Amdahl's law, which gives the theoretical speedup in the execution of a computing workload based on the number of processors available and the portion of the program that can make use of parallelization.

It might be a good idea to first create a virtual environment to prevent dependency conflicts. To create a virtual environment in a directory named `.virtualenvs`, run
```sh
python -m venv ~/.virtualenvs/jupyterlab
```
Replace `~/.virtualenvs` with whatever path you wish to save your virtual environments to.

Then activate the environment with
```sh
source ~/.virtualenvs/jupyterlab/bin/activate
```

Now you can install the required dependencies by running
```sh
pip install requirements.txt
```

To access the notebook via JupyterLab, run
```sh
jupyter lab
```
