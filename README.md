# Dotfiles

These dotfiles configure a minimal zsh environment. A companion `.macos` script can configure system defaults on macOS.
Finder hides files that start with a period, so the repository may look empty when opened normally. Use `ls -a` or press `Cmd+Shift+.` in Finder to reveal them.

## Contents

- `.zshrc` – a small zsh configuration providing a coloured prompt.
- `.macos` – a script that configures many macOS preferences.

## Running the macOS setup script

`.macos` is not sourced like a typical dotfile. To run it:

```bash
# Make the script executable (only once)
chmod +x .macos

# Run it with sudo so all settings can be applied
sudo ./.macos
```

Pass `--no-restart` if you do not want affected applications to restart
automatically.


