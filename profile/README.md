<picture>
  <source media="(prefers-color-scheme: dark)" srcset="logo-dark.png">
  <img alt="moat" src="logo-light.png" width="160">
</picture>

A rule language for XDP firewalls. Write rules, test them against packets,
load them into the kernel.

- [moat](https://github.com/moatfw/moat): the language and the `moat`
  toolchain, which checks, tests, compiles and loads rule files.
- [moat-examples](https://github.com/moatfw/moat-examples): rulesets for
  DDoS vectors, game servers and host administration, each with case files.
- [moat-vscode](https://github.com/moatfw/moat-vscode): the VS Code
  extension, with highlighting and diagnostics through `moat lsp`.
- [tree-sitter-moat](https://github.com/moatfw/tree-sitter-moat): a
  tree-sitter grammar for Neovim, Helix, Zed and other editors.

Documentation is at [moatfw.dev](https://moatfw.dev), and the
[install guide](https://moatfw.dev/docs/install) has the apt repository
and the packages.

moat is a [PlaySafe Networks](https://playsafe.dev) project, built for
the servers we protect and shared so anyone can use it.
