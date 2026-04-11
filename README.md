# zsh-fnm

Zsh plugin that initializes [fnm](https://github.com/Schniz/fnm) with shell completions and automatic version switching on `cd` via `--use-on-cd`.

## Installation with zgen

```
# ...
if ! zgen saved; then
    # ...
    zgen load davidparsson/zsh-fnm
    # ...
    
    zgen save
fi
```
