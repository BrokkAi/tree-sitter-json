# Brokk's JSON Grammar for Tree-sitter

[![CI][ci]](https://github.com/BrokkAi/tree-sitter-json/actions/workflows/ci.yml)
[![crates][crates]](https://crates.io/crates/brokk-tree-sitter-json)
[![docs.rs][docs]](https://docs.rs/brokk-tree-sitter-json)

This is the **Brokk-owned and independently maintained fork** of
[`tree-sitter/tree-sitter-json`](https://github.com/tree-sitter/tree-sitter-json),
a JSON grammar for [Tree-sitter](https://tree-sitter.github.io/tree-sitter/).
Brokk maintains this fork for its code-intelligence tooling and publishes the
Rust package as
[`brokk-tree-sitter-json`](https://crates.io/crates/brokk-tree-sitter-json).
It may intentionally diverge from upstream to support correctness required by
Brokk, including RFC 8259 whitespace and exponent handling.

Try the grammar in [Brokk's web playground](https://brokkai.github.io/tree-sitter-json/).

The Rust binding prefixes its native parser symbol so it can coexist with the
upstream `tree-sitter-json` crate in one executable. The npm and Python
bindings retain their upstream-compatible package names for compatibility.

[ci]: https://img.shields.io/github/actions/workflow/status/BrokkAi/tree-sitter-json/ci.yml?logo=github&label=CI
[crates]: https://img.shields.io/crates/v/brokk-tree-sitter-json?logo=rust
[docs]: https://img.shields.io/docsrs/brokk-tree-sitter-json?logo=docs.rs
