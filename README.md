# asdf-keycloak

[![Build Status](https://github.com/marquicus/asdf-keycloak/workflows/Main%20workflow/badge.svg)](https://github.com/marquicus/asdf-keycloak/workflows/Main%20workflow/badge.svg)

Keycloak plugin for [asdf-vm](https://github.com/asdf-vm/asdf) 


## Install

```bash
asdf plugin add keycloak https://github.com/marquicus/asdf-keycloak.git
```

## Use

```bash
# Install a packaged release

asdf install keycloak 16.1.1 # tag of specific version
asdf install keycloak latest # latest tag

```

Check asdf readme for instructions on how to install & manage versions of keycloak.

## Use Case

Useful for performing [management tasks](https://www.keycloak.org/docs/latest/server_admin/index.html#admin-cli) with different keycloak versions

```bash
# keycloak <17.x
kcadm.sh config credentials --server "https://my-keycloak/auth" --realm master --user admin
# keycloak >=17.x
kcadm.sh config credentials --server "https://my-keycloak/" --realm master --user admin
```

## License

See `LICENSE`
