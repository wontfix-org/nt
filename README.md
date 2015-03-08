# nscreen tmux bundle

Provides easy access to named tmux session with autocompletion of running sessions, as well as optional tmux configs on a per-name basis

# Usage

	nt mysessionname

Opens a new tmux session with the given name. As long as the session is alive, the same command will now attach to the session (detaching it from the previously attached terminal)

# Topic configs

If you create a file ~/.tmux-$NAME, will make nt use that config file for a session with $NAME.
