# asdf-kn

Plugin for [asdf](https://github.com/asdf-vm/asdf) Package Manager, install [knative.dev](https://knative.dev/) CLI.

## Install

Look for the Latest Release of [knative/client](https://github.com/knative/client/releases).

```sh
asdf plugin-add kn https://github.com/nolte/asdf-kn.git

asdf install kn 0.20.0
```

## Development


Direct call, for local development.
```sh
ASDF_INSTALL_TYPE=test \
  ASDF_INSTALL_VERSION=0.20.0 \
  ASDF_INSTALL_PATH=/tmp/plugin \
  ./bin/install
```
