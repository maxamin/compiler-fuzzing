# Glossary

- **Miscompilation (wrong-code bug):** the compiler accepts a program and emits code whose behaviour differs from the language semantics.
- **ICE (internal compiler error):** a compiler crash or assertion failure.
- **Undefined behaviour (UB):** program behaviour the language standard does not constrain; differences under UB are not compiler bugs.
- **Differential testing:** comparing the behaviour of the same program under different compilers, versions or flags.
- **Equivalence Modulo Inputs (EMI):** generating variants that must behave identically on a fixed input by changing code unexecuted on that input.
- **Interestingness test:** script used by a reducer that decides whether a candidate still shows the bug.
- **Test-case reduction:** automatic shrinking of a failing input while preserving the failure.
- **Bisection:** binary search over version history to find the commit that introduced a bug.
- **Miri:** an interpreter for Rust MIR that detects undefined behaviour.
- **Via-IR:** Solidity's compilation pipeline that goes through the Yul intermediate language.
- **Soundness hole:** a type-system or borrow-checker flaw that lets safe code cause undefined behaviour.
- **Translation validation:** checking that a specific compiled output refines its input, rather than verifying the compiler once.
