# Setting up the Virtual Environment for Python
----------------------------------------------

In this document i gonna show you how to set up the virtual environment for python.

- In this docs im going to give steps to setup the venv in unix/linux and macos.

- For windows please refer to the [windows](https://python-for-beginners.com/virtual-environments-in-python)


## Setting up the Virtual Environment for Python
----------------------------------------------

```bash
python3 -m venv venv
source venv/bin/activate
```
- To upgrade the pip in venv
```bash
python -m pip install --upgrade pip

# to check the pip version
pip --version
```

You can use `uv` to mangage the venv and other tools.

```bash
# on windows
powershell -c "irm https://astral.sh/uv/install.ps1 | iex"

# with pip
pip install uv

# with conda
conda install -c conda-forge uv

# with Homebrew
brew install uv

# to create a virtual environment
uv venv

# activation of the virtual environment

# on macos and linux
source venv/bin/activate

#on windows
.\venv\Scripts\activate
```