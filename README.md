<div align="center">

<h1> asdf-pyapp ![Build](https://github.com/amrox/asdf-pyapp/workflows/Build/badge.svg) ![Lint](https://github.com/amrox/asdf-pyapp/workflows/Lint/badge.svg) </h1>

[pyapp](https://github.com/amrox/pyapp) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

<h2> WARNING: The README is still boilerplate from the template and is not accurate yet. </h2>

# Contents

- [Contents](#contents)
- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add pyapp
# or
asdf plugin add pyapp https://github.com/amrox/asdf-pyapp.git
```

pyapp:

```shell
# Show all installable versions
asdf list-all pyapp

# Install specific version
asdf install pyapp latest

# Set a version globally (on your ~/.tool-versions file)
asdf global pyapp latest

# Now pyapp commands are available
cowsay Hi!
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/amrox/asdf-pyapp/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Andy Mroczkowski](https://github.com/amrox/)
