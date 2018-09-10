# fb-pol-ads
Examining ProPublica's Facebook Political Adverstisment data (as part of an Innovation in Focus series).

## Dependencies

Dependencies for this project are managed via [pipenv](https://pipenv.readthedocs.io/en/latest/).

Suggested setup for macOS:

### 1. Install Homebrew

Homebrew is an un-official package manager for macOS:

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### 2. Install pyenv

[pyenv](https://github.com/pyenv/pyenv) helps you manage different versions of Python running on the same machine.

```
brew update
brew install pyenv
```

Then follow the additional steps outlined [here](https://github.com/pyenv/pyenv#basic-github-checkout) staring with step 3.

### 3. Install pyenv-virtualenv

https://github.com/pyenv/pyenv-virtualenv#installing-with-homebrew-for-os-x-users

```
brew install pyenv-virtualenv
```

You will then need to add:

```
eval "$(pyenv init -)"
eval "$(pyenv virtualenv-init -)"
```

to your shell profile. Most likely this is `.bash_profile` in your home directory ([here](https://github.com/pyenv/pyenv-virtualenv#installing-as-a-pyenv-plugin) for more details).

### 4. Install pipenv

```
brew install pipenv
```

### 5. Clone the repo

This will create a local copy of project directory in your present working directory.

```
git clone https://github.com/rji-futures-lab/fb-pol-ads.git
```

### 6. Start your shell

This should initiate the creation of your virtual environment:

```
pipenv shell
```

### 7. Start a local jupyter notebook server

```
jupyter notebook
```
