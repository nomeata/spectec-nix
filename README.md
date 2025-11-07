# nix shell for spectec

This is my simple nix shell for working on
https://github.com/Wasm-DSL/spectec/tree/main/spectec

I use it using `devenv`:
```
~/build/spectec/spectec $ cat .envrc
use flake ../../spectec-nix
~/build/spectec/spectec $ cat ../.git/info/exclude
.envrc
```
