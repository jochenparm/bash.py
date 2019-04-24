# bash.py
## An inline Bash script runner, for Python.

### Example Usage

```pycon
>>> import bash

>>> bash.run("echo hi")
<BashProcess pid=24108 return_code=0>

>>> _.output
'hi\n'
```

### Installation

```shell
$ pipenv install bash.py
```

### Demo

Try `bash.py` interactively in this online demo:

[![](https://cdn-images-1.medium.com/max/1600/1*cI91DR6og9iF06hBrHKINg.png)](https://notebooks.ai/demo/gh/martinzugnoni/bash.py)
