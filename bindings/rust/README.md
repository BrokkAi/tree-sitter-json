# JSON Grammar for Tree-sitter

This crate provides Brokk's independently maintained package of the
[`tree-sitter/tree-sitter-json`](https://github.com/tree-sitter/tree-sitter-json)
grammar. It publishes the Rust binding as `brokk-tree-sitter-json` while
retaining the `tree_sitter_json` Rust import path through Cargo's package-name
mapping.

To use this crate, add it to the `[dependencies]` section of your
`Cargo.toml`:

```toml
tree-sitter = "0.25"
tree-sitter-json = { package = "brokk-tree-sitter-json", version = "=0.24.9" }
```

Typically, use the `LANGUAGE` constant with a tree-sitter `Parser`:

```rust
let mut parser = tree_sitter::Parser::new();
parser
    .set_language(&tree_sitter_json::LANGUAGE.into())
    .expect("Error loading JSON grammar");
```
