# vpype-rerun

This plug-in integrates the [Rerun viewer](https://github.com/rerun-io/rerun) in [`vpype`](https://github.com/abey79/vpype).


## Why?

Mostly for testing purpose on the Rerun side. This plug-in makes it easy to log large quantities of [2D line strips](https://www.rerun.io/docs/reference/data_types/linestrip2d) to the Rerun viewer, which is useful for stress-testing, etc.


## Installation

See the [installation instructions](https://vpype.readthedocs.io/en/latest/install.html) for information on how
to install `vpype` (TL;DR: `pipx install "vpype[all]"`).

If *vpype* was installed using pipx, use the following command:

```bash
$ pipx inject vpype vpype-rerun
```

If *vpype* was installed using pip in a virtual environment, activate the virtual environment and use the following command:

```bash
$ pip install vpype-rerun
```

## Documentation

The complete plug-in documentation is available directly in the CLI help:

```bash
$ vpype rerun --help
```


## License

See the [LICENSE](LICENSE) file for details.
