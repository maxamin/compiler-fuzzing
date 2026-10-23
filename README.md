# Compiler Fuzzing

> Csmith, YARPGen and differential testing of C, Rust, Solidity and Vyper compilers, including miscompilation hunting.

## Contents

<!-- toc:start -->
1. [Miscompilations versus Crashes](chapters/01-miscompilations-vs-crashes.md)
2. [Random Program Generation with Csmith and YARPGen](chapters/02-csmith-and-yarpgen.md)
3. [Equivalence Modulo Inputs and Test-Case Reduction](chapters/03-emi-and-test-case-reduction.md)
4. [Fuzzing the Rust Compiler](chapters/04-fuzzing-rustc.md)
5. [Smart Contract Compilers: solc and Vyper](chapters/05-solidity-and-vyper-compilers.md)
6. [LLM-Generated Programs and a Compiler Fuzzing Programme](chapters/06-llm-programs-and-programme.md)
<!-- toc:end -->

## How to read this

Read chapters in order, or jump to what you need. Every chapter ends with exercises and further reading. See [RESOURCES.md](RESOURCES.md) and [GLOSSARY.md](GLOSSARY.md).

## Build

```bash
mdbook serve   # optional: renders SUMMARY.md as a website
```

## License

Text: CC BY-SA 4.0. Code snippets: MIT. See [LICENSE](LICENSE).
