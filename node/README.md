# kts-node

A new SRML-based Substrate node, ready for hacking.

## Install and build

```
$ git clone git@github.com/Trinkler/kts
$ ./init.sh
$ ./build.sh
$ cargo build
```

## Run local node

```
$ export PATH=$(pwd)/target/debug:$PATH
$ kts --chain=local --key Alice --validator
```
