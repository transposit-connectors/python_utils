# pylint

This is a linter for python. It points out common problems (like undefined variables) which can save you time.

## Installation

Assuming you have python3 installed:

`pip3.7 install pylint`

More here https://www.pylint.org/

Copy the `.pylintrc` file in this repo to your home directory.

## Usage

* Checkout your workflow using git.
* Go to the top level directory of the workflow.
* Run pylint: `pylint src/*.py`
* Fix any issues.
* Commit.
* Push your code up
* Reload dev console in your browser, if applicable. *If you don't do this, you'll lose your work next time you touch the code in the dev console.*
