tmux-folder
===========

configs for tmux

Place the file tmux.conf in either ~/ for user settings, or /etc/ for global settings

Add to your bash.rc:
  TERM=screen-256color
  [[ -z "$TMUX" ]] && exec tmux
