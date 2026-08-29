# dotfiles-atuin

Config for [atuin](https://atuin.sh) (shell history sync/search), including a Claude Code hook (see the `claude` submodule) that logs bash tool calls into atuin history.

Part of the [dotfiles-arch](https://github.com/SaratAngajalaoffl/dotfiles-arch) multi-repo dotfiles system.

## Layout

- `config/config.toml` → `~/.config/atuin/config.toml` (see `.links`)

Atuin itself is installed via its official installer, not a distro package — shell integration (`atuin init zsh`) lives in the `zsh` submodule.

## Setup

Atuin sync requires a one-time account registration/login on each machine — see `.setup` for the exact commands. Everything else is applied by the parent repo's `install.sh`.
