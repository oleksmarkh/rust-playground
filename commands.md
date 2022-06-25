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
  "rust-playground/2_guessing_game/Cargo.toml",
  "rust-playground/3_variables/Cargo.toml",
]
```
