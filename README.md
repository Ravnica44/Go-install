```shell
sudo apt update && sudo apt install curl git mercurial make binutils bison gcc
```

```shell
bash < <(curl -s -S -L https://raw.githubusercontent.com/moovweb/gvm/master/binscripts/gvm-installer)
```

```shell
export GVM_ROOT="$HOME/.gvm"
[[ -s "$GVM_ROOT/scripts/gvm" ]] && source "$GVM_ROOT/scripts/gvm"
```

```shell
source ~/.bashrc
```

```shell
gvm selfupdate
```

```shell
gvm listall
```

```shell
gvm list
```

```shell
gvm uninstall goXX.XX
```

```shell
gvm install go1.21.0 -B
gvm use go1.21.0 --default
```

```shell
gvm install go1.22.6 -B
gvm use go1.22.6 --default
```

```shell
gvm install go1.24.3
gvm use go1.24.3 --default
```

```shell
gvm uninstall go1.21.0
```

```shell
go version
```
