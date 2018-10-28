# memo

## Building

### Ubuntu 18.04

- http://www.loveruby.net/ja/stdcompiler/
- https://github.com/aamine/cbc
- https://github.com/leungwensen/cbc-ubuntu-64bit/commit/c01e3ff69
  - fix build

```sh
sudo apt install ant
make
./install.sh ~/usr/opt/cbc
```

### macOS (gave up)

branch: darwin

```sh
# https://javacc.org/download
wget https://javacc.org/downloads/javacc-6.0.zip
unzip javacc-6.0.zip
brew install ant javacc
make
```
