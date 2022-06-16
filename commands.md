# commands
```bash
$ rustc --version
$ rustup update

$ cargo new <...> && cd <...>
$ cargo build [--release]
$ cargo run
$ cargo check
$ cargo update
$ cargo doc --open
```

# settings
## rust-analyzer VSCode extension
`~/Library/Application Support/Code/User/settings.json`:

```json
...
"rust-analyzer.linkedProjects": [
  "/.../rust-playground/guessing_game/Cargo.toml"
]
```
