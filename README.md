CIFAR10 Hands-On
----------------

This hands-on was prepared for one of my presentations that took place on Computer
 Vision's mini-course at student's orgranization called ["Gradient"](http://gradient.eti.pg.gda.pl/)
 (Gdańsk University of Technology).

Before running this hands-on, please recall the materials from previous meetings,
 especially my "Introduction to CNNs", which you can find in the root directory
 of the repository. HTML version with all the GIFs is available
 [here](https://mega.nz/#%21H4IEnZKJ%21so0Czkp8lcLWCt0o3O912WnKZBFjkvZFeJG23kITpig).

## Prerequisites

What do you need to install to run this hands-on?

 - Linux/macOS,
 - Python 3.5+,
 - Virtualenv (nice to have).

**Note:** PyTorch doesn't officially support Windows! For more information how to
 use it on Windows, please refer to this [Issue on GitHub](https://github.com/pytorch/pytorch/issues/494).
 It's highly recommended to use Linux/macOS instead, even in the Virtual Machine.

**Steps to follow:**

1. Install all needed packages.

 - into local environment (in order not to mess with global Python packages):

```bash
$ virtualenv -p python3 venv
$ . venv/bin/activate
(venv) $ pip install -r requirements.txt
```

 - ... **OR** into global Python packages:

```bash
$ pip install -r requirements.txt
```

2. Install PyTorch (it's needed to do separately):

 - Open official [PyTorch documentation](http://pytorch.org/#pip-install-pytorch),
 - In the section "Get Started" select your Operating System,
 - Choose "pip" as your Package Manager,
 - Select Python version which you use (`python --version`),
 - Select CUDA version (not needed for this hands-on),
 - Run commands that will show you below the form.

Now, you're ready to go!

## How to run this hands-on?

Once your environment is ready, it's time to open Jupyter Notebook
 with the hands-on:

```bash
(venv) $ venv/bin/jupyter notebook
```

Once your browser will open by itself, select the notebook called `CIFAR10 Hands-on.ipynb`
 and follow the instructions inside of it.

