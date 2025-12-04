# Installing `uv`

```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```


# uv Commands

| **uv Command**                | **Explanation**                                                               |
| ----------------------------- | ----------------------------------------------------------------------------- |
| `uv --version`                | Show the installed version of uv.                                             |
| `uv init`                     | Create a new Python project with `pyproject.toml`.                            |
| `uv add <package>`            | Add a dependency (like `poetry add`).                                         |
| `uv remove <package>`         | Remove a dependency.                                                          |
| `uv sync`                     | Install dependencies and create/update `.venv`.                               |
| `uv run <command>`            | Run a command inside the uv-managed virtual environment.                      |
| `uv python install <version>` | Install a Python version using uv.                                            |
| `uv python list`              | List installed Python versions.                                               |
| `uv venv`                     | Create a virtual environment (`.venv` by default if configured).              |
| `uv lock`                     | Generate or update the `uv.lock` file.                                        |
| `uv pip install <pkg>`        | Use uv's ultra-fast pip backend to install packages (compat with pip syntax). |
| `uv cache clean`              | Clear cached packages and wheels.                                             |
| `uv tool install <package>`   | Install global CLI tools (similar to `pipx install`).                         |
| `uv tool list`                | List installed tools via uv.                                                  |
| `uv config --list`            | Show all current uv settings.                                                 |


