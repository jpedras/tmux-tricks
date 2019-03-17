# tmux-tricks

Some usefull tmux commands assuming default config.

## Select part of buffer and paste into vi

```
ctrl+B
[       - enter vi copy mode
(move to where you want to start copying)
<space>	- select start copy point
<enter>	- select end copy point
(open vi and select insert mode)
ctrl+B
]       - paste into vi
```
