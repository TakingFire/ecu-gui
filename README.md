Custom GUI for [uraniumwolf22/FuelLoadSimulation](https://github.com/uraniumwolf22/FuelLoadSimulation).

Building (native):
```sh
cargo build
```

Cross-building for `aarch64`:
```sh
RUSTFLAGS="-Clinker=aarch64-linux-gnu-gcc" cargo build --release --target aarch64-unknown-linux-gnu
```
