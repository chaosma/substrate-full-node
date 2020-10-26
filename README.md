# Substrate Full Node

Get the required compiler version and wasm component before compiling.

```
rustup install nightly-2020-10-06
rustup target add wasm32-unknown-unknown --toolchain nightly-2020-10-06

# fix environmental package bug if it happens
cargo update -p environmental

# compile
cargo build --release

# run a local node
./target/release/substrate --dev
```
