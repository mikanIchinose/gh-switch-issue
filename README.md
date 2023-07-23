# gh-switch-issue

1. search issue assigned with you
1. select issue
1. switch feature/{{issue-number}}
1. first commit for four-keys metrics

## install

```shell
gh extension install mikanIchinose/gh-switch-issue
```

## setup

```shell
echo 'export GH_ISSUE_ASIGNEE="{{your github id}}"' >> $HOME/.zshrc
```

## prerequirement

- [gum](https://github.com/charmbracelet/gum)

## usage

```sh
gh switch-issue
```
