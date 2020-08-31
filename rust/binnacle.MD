export RUSTUP_IO_THREADS=1
curl https://sh.rustup.rs -sSf | sh


rustc main.rs

./main

source $HOME/.cargo/env