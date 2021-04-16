1) для подключения к someinternalhost в одну команду -  ssh -t -A id_ed25519@130.193.50.68 "ssh 10.130.0.35"

The -t is necessary in order to create a pseudo-tty for bash to use as an interactive shell
