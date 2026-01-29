<div align="center">

# asdf-keep-sorted [![Build](https://github.com/jtzero/asdf-keep-sorted/actions/workflows/build.yml/badge.svg)](https://github.com/jtzero/asdf-keep-sorted/actions/workflows/build.yml) [![Lint](https://github.com/jtzero/asdf-keep-sorted/actions/workflows/lint.yml/badge.svg)](https://github.com/jtzero/asdf-keep-sorted/actions/workflows/lint.yml)

[keep-sorted](https://github.com/google/keep-sorted) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add keep-sorted
# or
asdf plugin add keep-sorted https://github.com/jtzero/asdf-keep-sorted.git
```

keep-sorted:

```shell
# Show all installable versions
asdf list-all keep-sorted

# Install specific version
asdf install keep-sorted latest

# Set a version globally (on your ~/.tool-versions file)
asdf global keep-sorted latest

# Now keep-sorted commands are available
keep-sorted --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/jtzero/asdf-keep-sorted/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [jtzero ?](https://github.com/jtzero/)
