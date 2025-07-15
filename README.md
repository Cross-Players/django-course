# 1. Install homebrew
`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`
# 2. Install python
`brew install pyenv`
`pyenv install 3.9.6`
`echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile`
# 3. Create venv file
### Virtual environment to avoid conflict module with differences python project ###
`py -m venv .venv`
