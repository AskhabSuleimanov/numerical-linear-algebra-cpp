# Numerical Linear Algebra and Parallel C++

C++ coursework implementations of numerical linear-algebra algorithms, with sequential and multithreaded variants.

## Projects

| Directory | Topic |
| --- | --- |
| `EigenValues` | Matrix input, tridiagonalization, sign-change counting, and eigenvalue computation |
| `Jordan` | Sequential Jordan-style matrix transformation |
| `JordanMultithread` | Multithreaded Jordan transformation using POSIX threads |
| `Threads` | Additional threaded matrix-processing experiments |
| `SequenceMax` | A templated sequence utility and maximum-search exercise |

## Build and Run

Each directory has its own `Makefile`:

```bash
cd EigenValues
make
./a.out
```

The threaded projects require a compiler with POSIX threads support; their Makefiles link with `-pthread`.

To remove generated objects and binaries where a clean target is provided:

```bash
make clean
```

## Input

Matrix-based programs read example values from the local `input.txt` files. Review the corresponding `tests.cpp` file for the expected dimensions and invocation pattern.

## Notes

This is an academic archive. Generated object files and binaries are retained from the original work, but the C++ source and Makefiles are the canonical implementation.
