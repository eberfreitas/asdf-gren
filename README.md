<div align="center">

# asdf-gren [![Build](https://github.com/eberfreitas/asdf-gren/actions/workflows/build.yml/badge.svg)](https://github.com/eberfreitas/asdf-gren/actions/workflows/build.yml) [![Lint](https://github.com/eberfreitas/asdf-gren/actions/workflows/lint.yml/badge.svg)](https://github.com/eberfreitas/asdf-gren/actions/workflows/lint.yml)

[gren](https://gren-lang.org/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Install](#install)
- [License](#license)

# Install

Plugin:

```shell
asdf plugin add gren https://github.com/eberfreitas/asdf-gren.git
```

gren:

```shell
# Show all installable versions
asdf list-all gren

# Install specific version
asdf install gren latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gren latest

# Now gren commands are available
gren --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# License

See [LICENSE](LICENSE) © [Éber Freitas Dias](https://github.com/eberfreitas/)
