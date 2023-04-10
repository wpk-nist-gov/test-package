```{highlight} shell
```

# Installation

## Stable release

To install testpackage, run this command in your terminal:

```console
$ pip install testpackage
```

or

```console
$ conda install -c wpk-nist testpackage
```

This is the preferred method to install testpackage, as it will always install the most recent stable release.

If you don't have [pip] installed, this [Python installation guide] can guide
you through the process.

## From sources

The sources for testpackage can be downloaded from the [Github repo].

You can either clone the public repository:

```console
$ git clone git://github.com/wpk-nist-gov/testpackage.git
```

Once you have a copy of the source, you can install it with:

```console
$ pip install .
```

To install dependencies with conda/mamba, use:

```
.. code-block:: console
```

> \$ conda/mamba env create -n \{name} -f environment.yaml
> \$ pip install . --no-deps

To install an editable version, add the `-e` option to pip.

[github repo]: https://github.com/wpk-nist-gov/testpackage
[pip]: https://pip.pypa.io
[python installation guide]: http://docs.python-guide.org/en/latest/starting/installation/
