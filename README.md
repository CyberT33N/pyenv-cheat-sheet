# pyenv-cheat-sheet



## pyenv
- https://github.com/pyenv/pyenv?tab=readme-ov-file#installation


<br><br>

### Install
```shell
curl https://pyenv.run | bash

# Add to ~/.bashrc & ~/.zshrc
export PYENV_ROOT="$HOME/.pyenv"
[[ -d $PYENV_ROOT/bin ]] && export PATH="$PYENV_ROOT/bin:$PATH"
eval "$(pyenv init -)"

# restart shell
```

<br><br>

#### Install specific python version
```shell
pyenv install 3.9
```

<br><br>

#### Switch specific python version
- https://github.com/pyenv/pyenv?tab=readme-ov-file#switch-between-python-versions
```shell
pyenv shell <version> -- select just for current shell session
pyenv local <version> -- automatically select whenever you are in the current directory (or its subdirectories)
pyenv global <version> -- select globally for your user account
```


