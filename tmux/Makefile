all: \
	plugins/tpm \
	plugins/tmux-sensible \
	plugins/tmux-yank

plugins/tpm:
	git clone https://github.com/tmux-plugins/tpm $@
plugins/tmux-sensible:
	git clone https://github.com/tmux-plugins/tmux-sensible $@
plugins/tmux-yank:
	git clone https://github.com/tmux-plugins/tmux-yank $@

clean:
	rm -rf plugins/*

