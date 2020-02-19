# YAPF

A python formatter.

## Install

Visit https://github.com/google/yapf and follow instructions. I just installed on the command line.

## To use on your python operations

Currently just use the opinionated defaults.

* Use git to pull down the code repository
* Run yapf
* Commit
* Push it up
* Reload dev console in your browser, if applicable. *If you don't do this, you'll lose your work next time you touch the code in the dev console.*

## Helper scripts

You can clone yapf to a directory (here called `Y_DIR`) and then create this shell script (`runyapf.sh`):

```
#!/bin/sh

Y_DIR=$HOME/work/mc/yapf
PYTHONPATH=$Y_DIR python3 $Y_DIR/yapf -i $*
```

Add this to your path, and then you can go to your workflows root directory and run it: `runyapf.sh src/*.py` and then commit your changes as documented above.

