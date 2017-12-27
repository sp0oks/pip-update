# pip-update
A shell script solution to update installed pip modules.

Are you too lazy to look up every module you installed in pip to check if they need to be updated? I am. That's why I wrote `pip-update`, a small script to update everything in any of my pips.

## Requirements
For `pip-update` to work you should have any pip installed, this version works with `pip2`, `pip3` and `pypy3-pip`, but it can be made to work with any other.

## Usage
From your console, `./pip-update [options]` will run `pip install --upgrade` on all installed modules in the chosen pip version.

