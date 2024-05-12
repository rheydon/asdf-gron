<div align="center">

# asdf-gron [![Build](https://github.com/rheydon/asdf-gron/actions/workflows/build.yml/badge.svg)](https://github.com/rheydon/asdf-gron/actions/workflows/build.yml) [![Lint](https://github.com/rheydon/asdf-gron/actions/workflows/lint.yml/badge.svg)](https://github.com/rheydon/asdf-gron/actions/workflows/lint.yml)

[gron](https://github.com/tomnomnom/gron) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add gron
# or
asdf plugin add gron https://github.com/rheydon/asdf-gron.git
```

gron:

```shell
# Show all installable versions
asdf list-all gron

# Install specific version
asdf install gron latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gron latest

# Now gron commands are available
gron --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rheydon/asdf-gron/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [rheydon](https://github.com/rheydon/)
