# yq plugin

[yq](https://yqcli.io) plugin for [proto](https://github.com/moonrepo/proto).

## Installation

This is a community plugin and is thus not built-in to proto. In order to use it, first either add it to your global or project-based `.prototools` by running:

### Global install

```shell
proto plugin add yq "source:https://raw.githubusercontent.com/appthrust/proto-toml-plugins/main/yq/plugin.toml" --global
proto install yq
```

### Per-project install

```shell
proto plugin add yq "source:https://raw.githubusercontent.com/appthrust/proto-toml-plugins/main/yq/plugin.toml"
proto pin yq latest --resolve
```