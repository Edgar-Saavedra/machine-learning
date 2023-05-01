## Pyenv-virtualenv
```
brew update
brew install pyenv
brew install pyenv-virtualenv
pyenv --version
```

```
export PYENV_ROOT="$HOME/.pyenv"
export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init --path)"
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

```
pyenv install 3.11.3
```

```
pyenv local 3.10.0
pyenv which python
```

```
pyenv virtualenv 3.10.0 your-label-here
touch .python-version
echo your-label-here > .python-version
python --version
```

## Jupyter setup
```
pip install jupyterlab
jupyter-lab
```