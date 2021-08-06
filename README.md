# Bash completion support for the `mamba` command

This extends the
[`conda-bash-completion`](https://github.com/tartansandal/conda-bash-completion)
project to work with [`mamba`](https://mamba.readthedocs.io/en/latest/).
All we are doing here is adding support for the `repoquery` command and passing
off to the existing `conda-bash-completion` code.

Once this is submitted to conda-forge you should be able to install the feature
via the `mamba-bash-completion` package (and its dependencies):

```bash
mamba install -c conda-forge mamba-bash-completion
```

## NOTES

### `minimamba`

The `minimamba` executable is built on
[cli11](https://cliutils.github.io/CLI11/book/)
and has its own completion support built-in, so we are not going to mess with
that :wink:.
