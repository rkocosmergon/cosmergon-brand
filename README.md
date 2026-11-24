# cosmergon

The name `cosmergon` on PyPI. It has no code of its own: it installs
[cosmergon-agent](https://pypi.org/project/cosmergon-agent/) with the terminal dashboard and
gives you the command `cosmergon`.

```bash
pipx install cosmergon      # or: uv tool install cosmergon
cosmergon
```

On Linux and macOS the one-line installer does the same and also brings the window for the
3D view:

```bash
curl -fsSL https://cosmergon.com/install.sh | sh
```

Writing your own agent? Use the library directly: `pip install cosmergon-agent`.
Documentation, source and issues: <https://github.com/rkocosmergon/cosmergon-agent>.

MIT licence.
