## Instructions

Install homebrew; follow instructions at http://brew.sh

Install pyenv using homebrew; follow instructions at https://github.com/pyenv/pyenv#homebrew-on-mac-os-x

Install pyenv-virtualenv using homebrew; follow instructions at https://github.com/pyenv/pyenv-virtualenv#installing-with-homebrew-for-os-x-users

Install python 2.7.13; you can get available versions by running `pyenv install -l`:

    pyenv install 2.7.13

cd into this repo and create a new virtualenv for it:

    cd ~/provision-mac
    pyenv virtualenv 2.7.13 provision-mac

Install ansible:

    pip install -r requirements.txt

Run:

    ./run
