# Brokk's JSON Grammar for Tree-sitter

[![CI][ci]](https://github.com/BrokkAi/tree-sitter-json/actions/workflows/ci.yml)
[![discord][discord]](https://discord.gg/w7nTvsVJhm)
[![matrix][matrix]](https://matrix.to/#/#tree-sitter-chat:matrix.org)
[![crates][crates]](https://crates.io/crates/brokk-tree-sitter-json)
[![npm][npm]](https://www.npmjs.com/package/tree-sitter-json)
[![pypi][pypi]](https://pypi.org/project/tree-sitter-json)

This is the **Brokk-owned and independently maintained fork** of
[`tree-sitter/tree-sitter-json`](https://github.com/tree-sitter/tree-sitter-json),
a JSON grammar for [Tree-sitter](https://tree-sitter.github.io/tree-sitter/).
Brokk maintains this fork for its code-intelligence tooling and publishes the
Rust package as
[`brokk-tree-sitter-json`](https://crates.io/crates/brokk-tree-sitter-json).
It may intentionally diverge from upstream to support correctness required by
Brokk, including RFC 8259 whitespace and exponent handling.

The Rust binding prefixes its native parser symbol so it can coexist with the
upstream `tree-sitter-json` crate in one executable. The npm and Python
bindings retain their upstream-compatible package names for compatibility.

[ci]: https://img.shields.io/github/actions/workflow/status/BrokkAi/tree-sitter-json/ci.yml?logo=github&label=CI
[discord]: https://img.shields.io/discord/1063097320771698699?logo=discord&label=discord
[matrix]: https://img.shields.io/matrix/tree-sitter-chat%3Amatrix.org?logo=matrix&label=matrix
[npm]: https://img.shields.io/npm/v/tree-sitter-json?logo=npm
[crates]: https://img.shields.io/crates/v/brokk-tree-sitter-json?logo=rust
[pypi]: https://img.shields.io/pypi/v/tree-sitter-json?logo=pypi&logoColor=ffd242
