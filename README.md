# Django Course

## 1. Install homebrew

`/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"`

## 2. Install python

`brew install pyenv`
`pyenv install 3.9.6`
`echo 'export PATH="$PYENV_ROOT/bin:$PATH"' >> ~/.bash_profile`

add `alias pip=/opt/homebrew/bin/pip3

and  `alias python=/usr/bin/python3` in ~/.zshrc

## then `source ~/.zshrc`

## 3. Create venv file

### Virtual environment to avoid conflict module with differences python project

`python -m venv .venv`

`source .venv/bin/activate`

## 4. Install Django

### Update pip

`python -m pip install -U pip`
`python3 -m pip install --upgrade pip`

`python -m pip install Django`
`python`
`print(django.get_version())`

## 5. Create project

`python -m django startproject mysite django-course`
