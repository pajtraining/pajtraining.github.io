## Installation instruction for 'Introduction to solving biological problems with Python' course

### :memo: Dependencies

This only needs to be done once. To run the course, first download and install these dependencies:

- **Python3**: install Python 3 by downloading the latest version from https://www.python.org/

- **Git**: install Git by downloading the latest version from https://git-scm.com/downloads

Now clone the GitHub repository to copy the course materials onto your computer:

- **Clone** the GitHub repo [python-basic](https://github.com/pajtraining/python-basic.git):
```
git clone https://github.com/pajtraining/python-basic.git
cd python-basic/
```

- Create a **virtual environment** to install the python dependencies:
```bash
python3 -m venv venv
# activate your virtual environment
source venv/bin/activate
# update pip if needed
pip install --upgrade pip
# install jupyter
pip install jupyter
```

### :computer: Usage

Go to the directory where you've cloned this repository, activate your virtual environment and run jupyter.

Your web browser should automatically open with this url http://localhost:8888/tree where you see the directory tree of the course with all the jupyter notebooks.

```bash
cd python-basic
source venv/bin/activate
jupyter notebook
```

You are now setup to run the course and start your python journey! Congratulations :tada:

Click on the first notebook [python_basic_1_intro.ipynb](http://localhost:8888/notebooks/python_basic_1_intro.ipynb) and start reading.

To shutdown jupyter, type ctrl-C into the terminal you've ran `jupyter notebook`, answer `y` and press `enter`.

You may wish to deactivate the virtual environment, by entering into the terminal:
```
deactivate
```

### [:house: Back to the PajTraining home page](README.md)
