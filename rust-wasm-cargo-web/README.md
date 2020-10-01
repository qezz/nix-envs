# Rust, WASM

```
$ nix-shell default.nix

$ # Then you can run any cargo-web command. (You need to specify the target)
$ cargo-web build --target=wasm32-unknown-unknown
$ cargo-web start --target=wasm32-unknown-unknown
$ cargo-web deploy --target=wasm32-unknown-unknown
```

Based on https://gist.github.com/LightDiscord/aa8cb8e67ec9efbf9b20a9a3e9ebd007
