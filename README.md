## Getting Started

### Installing Dependencies

```
> cd PillCounter
> pipenv install
```

### Starting the Notebook Server

```
> pipenv run jupyter notebook
```

The server runs at http://localhost:8888 by default.

## FAQ

**I don't have Python 3.7 or pipenv**

Follow the guide for [Pipenv & Virtual Environments](https://docs.python-guide.org/dev/virtualenvs/)

**`pipenv` is not available in my shell**

Add the following to your `.bash_profile`:
```
export PATH=$PATH:/path/to/Python/3.7/bin
```

Then run:
```
> source ~/.bash_profile
> which pipenv

/path/to/pipenv/installation
```
It should output the location of the pipenv program file.
