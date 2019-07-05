# base16 color theme for tmux

A tmux base16 theme based on the work of [tmux-gruvbox](https://github.com/egel/tmux-gruvbox) and [base16](https://github.com/chriskempson/base16).

## Installation
These config snippets for the terminal multiplexer tmux should be added to your `~/.tmux.conf` configuration file.
Add this line in your ~/.tmux.conf :
source colors/base16-default-dark.conf

In most cases, you have to force tmux to assume the terminal supports 256 colours.
For this, start tmux as `tmux -2`.

This color scheme is tested with tmux >= 1.5. tmux 1.1 is reported as not working.
