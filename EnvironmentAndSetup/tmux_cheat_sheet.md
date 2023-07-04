# TMUX Cheat Sheet  

## Windows
Rename Window: `Ctrl+B+,`  
Create new Window: `Ctrl+B+C`  
Switch between windows: `Ctrl+B+<number>`  
Close Window: `exit`

## Panes
Split Windows Vertically: `Ctrl+B+%`  
Split Windows Horizontally: `Ctrl+B+"`  
Navigate subwindows (panes): c  
Show pane numbers: `Ctrl+B+Q`  
Move current pane left: `Ctrl+B+{`  
Move current pane right: `Ctrl+B+}`  

## Sessions
Open tmux as a named session: `tmux new -s <name>`  
To detach a tmux session: `Ctrl+B+D`  
View tmux sessions (from cli): `tmux ls`  
Re-attach to session (from cli): `tmux attach -t 0`  
Rename tmux sessions (from cli): `tmux rename-sesssion -t 0 <name>`  
Killing tmux sessions (from cli): `tmux kill-sesssion -t 0 <name>` 
__Where ‘0’ is your session id/name__