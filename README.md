# crowbar

* various parser combinators for sec logs

## dev (flakes)

```bash
# Dev shell
nix develop

# or just run directly
nix run

# or run via cargo
nix develop -c cargo run

# build
nix build
```

## dev (legacy nix)

```bash
# Dev shell
nix-shell

# run via cargo
nix-shell --run 'cargo run'

# build
nix-build
```

There's also a `bin/run` script which starts 'cargo watch'; it's used by VSCode as well (`Ctrl+Shift+B`).
