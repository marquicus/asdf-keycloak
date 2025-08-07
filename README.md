# asdf-keycloak

[![Build Status](https://github.com/marquicus/asdf-keycloak/workflows/Main%20workflow/badge.svg)](https://github.com/marquicus/asdf-keycloak/workflows/Main%20workflow/badge.svg)

Keycloak plugin for [asdf-vm](https://github.com/asdf-vm/asdf) 


## Install

```bash
asdf plugin add keycloak
```

## Use

```bash

# Install a pre-compiled release

asdf install keycloak 16.1.1 # tag of specific version
asdf install keycloak nightly # nightly tag
asdf install keycloak stable # stable tag

# Compile from source

asdf install keycloak ref:master # install from a branch
asdf install keycloak ref:f0eb3ca9163ad10753fbb75558b900a539f76e0d # or a commit
```

To "update" your `stable`, `nightly`, or a ref installation, you must first un-install and then re-install the desired version. You can create a few aliases to make this easier.

```bash
alias update-kc-stable='asdf uninstall keycloak stable && asdf install keycloak stable'
alias update-kc-nightly='asdf uninstall keycloak nightly && asdf install keycloak nightly'
alias update-kc-master='asdf uninstall keycloak ref:master && asdf install keycloak ref:master'
```

Check asdf readme for instructions on how to install & manage versions of keycloak.

## License

See `LICENSE`
