Here's your updated README, tailored for Flit:

# Flit 
This package is an example project for building a Python package (i.e., wheel or sdist).
It relies on [Flit](https://flit.readthedocs.io/en/latest/) as a build backend with pyproject.toml
for configuration.

## Commands:

Note: Like setuptools, flit doesn't manage your virtual environment. You'll need to create and activate one yourself (e.g. with [venv](https://docs.python.org/3/library/venv.html)) and install flit into it.

* Editable install:
```shell
flit install --symlink --deps=all
```
* Run code:
```shell
python -c "import flit_demo_package"
```
* Build:
```shell
flit build
```
* Upload to PyPI:
```shell
flit publish
```