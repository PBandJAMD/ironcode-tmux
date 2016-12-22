# ironcode-tmux
My tmux configuration and notes.

## Common Commands

### Built-in Commands

- `prefix + c` create new window
- `prefix + "` create new vertical split (think of two vertical lines)
- `prefix + %` create new horizontal split (think of bar as almost horizontal)
- `prefix + ,` rename window
- `prefix + ctrl (up arrow)` move maleable edge up (e.g. a bottom pane gets bigger, top pane gets smaller) (also works for other arrow keys)
- `prefix + [` enter copy mode
- `prefix + #` list all paste buffers
- `prefix + =` choose which buffer to paste interactively from a list.

### Custom Commands
- `prefix + r` reload configuration (i.e. reload _~/.tmux.conf_)
- `Ctrl + h` navigate to left pane (also works with j,k,l)

### In Copy Mode

- `<space>` start selection
- `v` start selection (custom command)
- `<enter>` copy selection

## Setup

Clone the directory in your home directory.

```
git clone git@github.com:salcode/ironcode-tmux.git ~/
```

Symlink `tmux.conf` to `~/.tmux.conf`

```
ln -sf ~/ironcode-tmux/tmux.conf ~/.tmux.conf
```
