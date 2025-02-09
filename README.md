sudo apt update && sudo apt install curl git mercurial make binutils bison gcc

bash < <(curl -s -S -L https://raw.githubusercontent.com/moovweb/gvm/master/binscripts/gvm-installer)

export GVM_ROOT="$HOME/.gvm"
[[ -s "$GVM_ROOT/scripts/gvm" ]] && source "$GVM_ROOT/scripts/gvm"

source ~/.bashrc

gvm selfupdate
gvm listall
gvm list
gvm uninstall goXX.XX

gvm install go1.21.0 -B
gvm use go1.21.0 --default

gvm install go1.22.0
gvm use go1.22.0 --default

gvm uninstall go1.21.0

go version
