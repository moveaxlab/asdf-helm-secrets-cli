<div align="center">

# asdf-helm-secrets-cli [![Build](https://github.com/moveaxlab/asdf-helm-secrets-cli/actions/workflows/build.yml/badge.svg)](https://github.com/moveaxlab/asdf-helm-secrets-cli/actions/workflows/build.yml) [![Lint](https://github.com/moveaxlab/asdf-helm-secrets-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/moveaxlab/asdf-helm-secrets-cli/actions/workflows/lint.yml)

[helm-secrets-cli](https://github.com/jkroepke/helm-secrets/wiki) plugin for the [asdf version manager](https://asdf-vm.com).

this plugin will install helm-secrets-cli plugin for helm: https://github.com/jkroepke/helm-secrets

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `helm`: helm must be installed in you system either via asdf/mise or globally.

# Install

Plugin:

```shell
asdf plugin add helm-secrets-cli
# or
asdf plugin add helm-secrets-cli https://github.com/moveaxlab/asdf-helm-secrets-cli.git
```

helm-secrets:

```shell
# Show all installable versions
asdf list-all helm-secrets-cli

# Install specific version
asdf install helm-secrets-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global helm-secrets-cli latest

# Now helm-secrets-cli is available
helm plugin list
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/moveaxlab/asdf-helm-secrets-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [moveax](https://github.com/moveaxlab/)