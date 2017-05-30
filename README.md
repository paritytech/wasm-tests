# wasm-tests

Replentishable collection of varios WASM compilable contract wxamples, both source and binary for integration testing in Parity.

## Prerequisites for manual building

### Rust

- rustc with `wasm32-unknown-emscripten` target - instruction to setup can be found [https://hackernoon.com/compiling-rust-to-webassembly-guide-411066a69fde](here)
- make sure `emcc` tool is in the `PATH` since build script uses it internally
- bash to run `./build_all.sh`

### C/C++
- to be updated