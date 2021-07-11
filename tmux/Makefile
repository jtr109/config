.PHONY: build

conf = $${HOME}/.tmux.conf
local_conf = $${HOME}/.tmux.conf.local

build: .tmux
	ln -sf $${PWD}/.tmux/.tmux.conf ${conf}
	ln -sf $${PWD}/.tmux.conf.local ${local_conf}

.tmux:
	git clone https://github.com/gpakosz/.tmux.git
