grep your tmux panes!

## Installation

Download `tgrep` from this repo and place it on your path.

## Usage

```
tgrep <grep arguments>
```

`tgrep` pops up a `tmux` pane chooser (using `tmux choose-tree`), then runs
`grep` against the content of that pane.

`tgrep` doesn't have any command line arguments of its own. Everything gets
passed down to `grep`.
