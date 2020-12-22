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
```