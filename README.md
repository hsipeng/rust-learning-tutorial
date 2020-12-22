# wasm_game_of_life

## build

```bash
wasm-pack build
```

## dev

```bash
cd www && yarn start
```


## test

```bash
cargo test
```

## bench

```bash
rustup install nightly
cargo +nightly bench | tee before.txt
cargo +nightly bench | tee after.txt
cargo install cargo-benchcmp
cargo benchcmp before.txt after.txt
```

## publish

```bash
wasm-pack publish
```