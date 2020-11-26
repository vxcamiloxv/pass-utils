# password-store utils

[Password-store][pass] utilities to extend their functionality, this contain a
[rofi][rofi] UI and a wrapper to disable clipboard manager and avoid store our
secrets in plain text!

## Requirements
- password-store
- rofi (optional)

## Usage

### passp

Clone this repo in for example `~/.scripts/` or `~/.local/bin/` and
add an alias or symlink pointing to `passp` e.g.

```sh
  alias pass="$HOME/.scripts/pass/passp"
```
or

```sh
  ln -s ~/.scripts/pass/passp ~/.local/bin/pass
```

for the symlink `~/.local/bin/` bus be added to your [$PATH][path]

### pass-rofi

Pass-rofi support direct invocation or via rofi [modi][modi] mode, by
default use `passp`.

Copy `passrofi.desktop` to `~/.local/share/applications` or add the script
path to `rofi.modi` configuration.

 [pass]: https://www.passwordstore.org
 [modi]: https://github.com/davatorium/rofi/wiki/mode-Specs
 [rofi]: https://github.com/davatorium/rofi
 [path]: http://www.linfo.org/path_env_var.html

