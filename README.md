# Bash completion support for the `mamba` command

This extends the
[`conda-bash-completion`](https://github.com/tartansandal/conda-bash-completion)
project to work with [`mamba`](https://mamba.readthedocs.io/en/latest/) by
adding support for the `repoquery` command and its options.

The easiest way to install this feature is via the `mamba-bash-completion`
package:

```bash
mamba install -c conda-forge mamba-bash-completion
```

This is really just a thin wrapper to tweak
[`conda-bash-completion`](https://github.com/tartansandal/conda-bash-completion)
so see that project for details.

## NOTES

### `minimamba`

The `minimamba` executable is built on
[cli11](https://cliutils.github.io/CLI11/book/) and has its own completion
support built-in, so we are not going to mess with that :wink:.

## Thanks

Thanks to @sixvable for introducing me to mamba by suggesting this
project. :smile:
