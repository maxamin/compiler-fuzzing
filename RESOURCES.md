# Resources

## Program generators and fuzzers
- [Csmith](https://github.com/csmith-project/csmith): random UB-free C program generator.
- [YARPGen](https://github.com/intel/yarpgen): generator for C/C++ targeting specific optimisations.
- [icemaker](https://github.com/matthiaskrgr/icemaker): ICE hunter for rustc and related tools.
- [Rustlantis](https://github.com/cbeuw/rustlantis): MIR-level differential tester for rustc.
- [OSS-Fuzz](https://google.github.io/oss-fuzz/): hosts fuzzers for many compilers and language tools, including Solidity.

## Reduction and validation
- [C-Reduce](https://github.com/csmith-project/creduce) and [cvise](https://github.com/marxin/cvise)
- [Miri](https://github.com/rust-lang/miri): Rust MIR interpreter and UB detector.
- [Alive2](https://github.com/AliveToolkit/alive2): translation validation for LLVM.
- [CompCert](https://compcert.org/): formally verified C compiler with a reference interpreter.

## Smart contract compilers
- [Solidity known bugs](https://docs.soliditylang.org/en/latest/bugs.html) and [via-IR changes](https://docs.soliditylang.org/en/latest/ir-breaking-changes.html)
- [Vyper documentation](https://docs.vyperlang.org/), [Titanoboa](https://github.com/vyperlang/titanoboa)
- [Foundry](https://book.getfoundry.sh/)

## Papers
- Yang, Chen, Eide, Regehr, "Finding and Understanding Bugs in C Compilers", PLDI 2011.
- Regehr et al., "Test-Case Reduction for C Compiler Bugs", PLDI 2012.
- Le, Afshari, Su, "Compiler Validation via Equivalence Modulo Inputs", PLDI 2014.
- Livinskii, Babokin, Regehr, "Random Testing for C and C++ Compilers with YARPGen", OOPSLA 2020.
- Chen et al., "A Survey of Compiler Testing", ACM Computing Surveys, 2020.
- Wang, Jung, "Rustlantis: Randomized Differential Testing of the Rust Compiler", OOPSLA 2024.
- Xia et al., "Fuzz4All: Universal Fuzzing with Large Language Models", ICSE 2024.
- Yang et al., "WhiteFox: White-box Compiler Fuzzing Empowered by Large Language Models", OOPSLA 2024.

## Related books in this wiki
- **browser-engine-fuzzing**, **ai-fuzzing-field-guide**, **rust-formal-verification**, **neurosymbolic-contract-verification**, **llm-smart-contract-vuln-research**
