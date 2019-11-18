## Jupyter Notebook Lesson

This is an exercise that corresponds to a lesson on using Jupyter notebooks.

This notebook demonstrates how to use Pandas to open a .csv file, and then graph data using Seaborn/Matplotlib libraries.

### Recommended Installation Instructions

The iPython notebook can be viewed using many different methods. To view online without installing anything, visit [Google Colab](https://colab.research.google.com/) and search for this Github repository.

### Install locally on a Mac

To run this notebook locally on a Mac, it's recommended to use [homebrew](https://brew.sh/) to install `pyenv` and `pipenv`. This will allow you to run this notebook in a virtual environment. 

```
brew install pyenv
```

To complete the pyenv setup, you'll need to modify your `.bash_profile`. The following command will automatically initiate pyenv's shims whenever you crate a new Terminal session.

```
echo -e 'if command -v pyenv 1>/dev/null 2>&1; then\n  eval "$(pyenv init -)"\nfi' >> ~/.bash_profile
```

Restart your Terminal.

Next, add Python 3.6.8 to your available Python versions.

```
pyenv install 3.6.8
```

Then, install **Pipenv**.

```
brew install pipenv
```

Lastly, clone/download this repository to your machine, navigate to the folder where you downloaded this repo, and then run:

```
pipenv shell
```

Once in the Python virtual environment, install included dependencies.

```
pipenv install
```

Run this notebook by launching Jupyter notebook.

```
jupyter notebook
```

To exit the shell, type `exit`. 


<small>Credit: <a href="https://www.kaggle.com/hugodarwood/epirecipes" target="_blank">Epicurious recipes via Kaggle</a>.</small>

