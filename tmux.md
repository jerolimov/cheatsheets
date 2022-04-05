# tmux-cheatsheet

Session -> Windows (shown as tabs) -> Panes

| CLI        | |
|------------|-|
| `tmux`     | Create a new session |
| `tmux a`   | Attach (join) session |
| `tmux ls`  | List all sessions |
| `tmux lsw` | List all windows |

| General shortcuts   | |
|---------------------|-|
| `ctrl+b` &nbsp; `:` | Command prompt |
| `ctrl+b` &nbsp; `d` | **Detach** (Leave tmux and keep session alive) |
| `ctrl+b` &nbsp; `?` | List all shortcuts |
| `ctrl+b` &nbsp; `[` | **Enter copy mode** |
| `ctrl+b` &nbsp; `]` | **Paste clipboard** |

| Session shortcuts   | |
|---------------------|-|
| `ctrl+b` &nbsp; `$` | **Set name for the current session** |
| `ctrl+b` &nbsp; `(` | Prev session |
| `ctrl+b` &nbsp; `)` | Next session |

| Window shortcuts    | |
|---------------------|-|
| `ctrl+b` &nbsp; `c` | **Create new window** |
| `ctrl+b` &nbsp; `,` | **Set name for the current window** |
| `ctrl+b` &nbsp; `p` | Prev window |
| `ctrl+b` &nbsp; `n` | Next window |
| `ctrl+b` &nbsp; `l` | Last window |
| `ctrl+b` &nbsp; 0-9 | Jump to window 0-9 |
| `ctrl+b` &nbsp; `w` | Select a window |
| `ctrl+b` &nbsp; `f` | Find a window |

| Pane shortcuts      | |
|---------------------|-|
| `ctrl+b` &nbsp; `%` | Vertical split (side by side) |
| `ctrl+b` &nbsp; `"` | Horizontal split (one below the other one) |
| `ctrl+b` &nbsp; cursor | Jump between panes |
| `ctrl+b` &nbsp; `{` or `}` | Swap panes |
| `ctrl+b` &nbsp; `+` | Break into own window |
| `ctrl+b` &nbsp; `z` | Zoom into |
| `ctrl+b` &nbsp; `x` | Close / Kill |
| `ctrl+b` &nbsp; `w` | Select a window |
