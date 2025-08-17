# copier-uv-python-project

A [copier](https://github.com/copier-org/copier) template for generating Python projects with [uv](https://docs.astral.sh/uv/).

## Tech stack

- [uv](https://docs.astral.sh/uv/)
- [pytest](https://docs.pytest.org/)
- [Ruff](https://docs.astral.sh/ruff/)
- [pyright](https://github.com/microsoft/pyright)

## Prerequisites

To generate a project, you need to have both `copier` and `uv` installed on your machine.

If you haven't installed `uv` yet, follow [uv's instruction guide](https://docs.astral.sh/uv/getting-started/installation/).

To install `copier` globally using `uv tool` subcommand, run:

```shell
uv tool install copier
```

For alternative installation methods, see [copier's offical documentation](https://copier.readthedocs.io/en/stable/#installation)

## Generating a project

To create a new project, run:

```shell
copier copy --trust gh:takuyaa/copier-uv-python-project /path/to/your-project
```

Note: The `--trust` option is required for installing dependencies after project generation.
