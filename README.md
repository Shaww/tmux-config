tmux configuration file with all the colour/visual settings deferred to third-party plugins.
Plugins managed by TPM, with powerline plugin by maglev.

`.tmux.conf` to be placed in the `~/`(home) directory.

Plugin management setting are placed at the bottom of the `.tmux.conf` file. The use the
plugin system, we need to clone `git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm`.
Note that the `.tmux` folder may not be present in the home directory.

With the plugins referenced inside `.tmux.conf`, much like what Vundle does, we can
get the plugin manager to download the plugins using `<mod> + <Shift>I`. Updates can
be done via `<mod> + <Shift>U`.
