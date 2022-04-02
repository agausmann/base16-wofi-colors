# base16-wofi-colors

An alternative to [base16-wofi] that provides a colors file instead of a
predetermined stylesheet.

## Usage

This guide assumes you're using the default paths for your wofi configuration.
If you use different config paths, I'm sure you know what you're doing :) but
just be sure to replace these paths with the correct ones.

1. Copy the desired theme from `themes/base16-<theme>.colors` to
`~/.cache/wal/colors`.

2. When building your stylesheet at `~/.config/wofi/style.css`, use
   `--wofi-color<n>` to reference the base16 color specified by `<n>`, and wofi
will insert it at that location in the file. Note that `<n>` is the color
number in decimal, not hex; for example, the color `base0A` would be referenced
with `--wofi-color10`. 

[base16-wofi]: https://git.sr.ht/~knezi/base16-wofi

