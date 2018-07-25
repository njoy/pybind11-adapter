# pybind11-adapter

A repository which adapts the [pybind11](https://github.com:pybind/pybind11) project for use in the NJOY21 build scheme.

Documentation about how to use pybind11 can be found in [pybind11.readthedocs.io](https://pybind11.readthedocs.io)

## Git Subtree

This repository uses a git subtree for the directory src. The remote from which the subtree is made is located at [git@github.com:pybind/pybind11.git]().

To facilitate updating the subtree when it gets updated upstream, do the following:

```
# This only needs to be done once
git remote add pybind11 https://github.com/pybind/pybind11.git

# Do this when you need to update the subtree
git subtree pull --prefix src pybind11 master --squash
```

## License

The code contained in this directory is covered by the license contained in the LICENSE file. The code in the src directory is covered by it's own LICENSE.
