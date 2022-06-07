# cheatsheets
cheat sheets for various tools/software

**Table of Contents**

- [git](https://github.com/aj-malcolm/cheatsheets#git)
- [Python](https://github.com/aj-malcolm/cheatsheets/blob/main/python.md#python)
  - [Documentation](https://github.com/aj-malcolm/cheatsheets/blob/main/python.md#documentation--insights)
  - [How-tos](https://github.com/aj-malcolm/cheatsheets/blob/main/python.md#how-to)


- [Sublime](https://github.com/aj-malcolm/cheatsheets#sublime)
- [Vim](https://github.com/aj-malcolm/cheatsheets#vim)
- [Windows Terminal](https://github.com/aj-malcolm/cheatsheets#windows-terminal)

## Git

| Command | Description |
| -- | -- |
| `git add --patch` | Interactively stage changes as a patch. |
| `git add -u` | The `-u` option will stage tracked and update files (unlike `git add .` which will stage all files, including untracked) |
| `git log main` | Show the log history for branch `main`.|
| `git log main..dev` | Show log for commits that are in branch `dev` and NOT in branch `main` |
| `git diff --cached` | `--cached` means show the changes in the cache/index (i.e. staged changes) against the current `HEAD`. `--staged` is a synonym for `--cached.` [source](https://stackoverflow.com/a/1587877) |
| `git diff --cached --color=always \| less -r` | `--color=always` tells git to include color codes even when outputting to a pip instead of tty. `-r` tells less to read color codes. |

## Sublime

### Editing

| Command | Description |
| -- | -- |
| `Ctrl` + `D` | Select and search for word under cursor |
| `Ctrl` + `Shift` + `D` | Duplicate line under cursor |
| `Ctrl` + `Shift` + `F` | Search all (folder or open files) |
| `Ctrl` + `[`/`]` | Indent line in direction |
| `Ctrl` + `/` | Comment out line(s) |
| `Ctrl` + `Alt` + `<up>`/`<down>` | Add another cursor in direction of arrow |

### Navigation

| Command | Description |
| -- | -- |
| `Ctrl` + `G` | Go to line number |
| `Ctrl` + `<num>` | Switch to column `<num>` in multi-column view |
| `Ctrl` + `K` then `Ctrl` + `<arrow>` | Switch to pane in direction of arrow |
| `Alt` + `<num>` | Switch to tab `<num>` |
| `Alt` + `-` | Go to previous cursor location |


## Vim

### Navigation

| Command | Description |
| -- | -- |
| `*`, `#` | search forward/backward |
| `zz` | center the current line and keep cursor in same column |
| `z.` | center current line and move cursor to first non-whitespace character |

### Completion

Completion can be done for:

| Command | Description |
| -- | -- |
| `i_CTRL-X_CTRL-L` |  Whole lines |
| `i_CTRL-X_CTRL-N` |  keywords in the current file |
| `i_CTRL-X_CTRL-K` |  keywords in 'dictionary |
| `i_CTRL-X_CTRL-T` |  keywords in 'thesaurus', thesaurus-style |
| `i_CTRL-X_CTRL-I` |  keywords in the current and included files |
| `i_CTRL-X_CTRL-]` |  tags |
| `i_CTRL-X_CTRL-F` |  file names |
| `i_CTRL-X_CTRL-D` |  definitions or macros |
| `i_CTRL-X_CTRL-V` |  Vim command-line |
| `i_CTRL-X_CTRL-U` |  User defined completion |
| `i_CTRL-X_CTRL-O` |  omni completion |
| `i_CTRL-X_s` |  Spelling suggestions |
| `i_CTRL-N`/`i_CTRL-P` |  keywords in 'complete-window' |

## Windows Terminal

| Command | Description |
| -- | -- |
| `alt` + `shift` + `=` | New pane (right) |
| `alt` + `shift` + `-` | New pane (btm) |
| `alt` + `shift` + `arrow` | Resize |
| `alt` + `arrow` | Change focus |
| `ctrl` + `shift` + `w` | Close pane |

