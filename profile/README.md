# Verona

![Verona calico cat](https://raw.githubusercontent.com/verona-project/.github/HEAD/profile/calico.png)

Verona is a statically typed systems programming language with S-expression
syntax, compile-time macros, and ahead-of-time native compilation through LLVM.
It brings together the flexibility of Lisp-style source forms, explicit types,
and native performance.

The language supports product and sum types, pattern matching, generic dispatch,
and protocols. Programs can compile to executables, object files, static
libraries, or shared libraries, with C interoperability for working with native
code.

```lisp
(function main () exit-code
  (+ 1 2))
```

This organization brings together Verona's libraries and tools:

- [Base](https://github.com/verona-project/base): core numeric, equality,
  ordering, and conversion protocols.
- [Foundation](https://github.com/verona-project/foundation): allocators, arenas,
  strings, binary data, and collections.
- [libc](https://github.com/verona-project/libc): bindings to the C standard library.
- [Testing](https://github.com/verona-project/testing): assertions, fixtures,
  and test runners written for Verona programs.
- [Formatter](https://github.com/verona-project/formatter) and
  [project tools](https://github.com/verona-project/project): native tools for
  formatting source and creating projects.

Explore the [language, compiler, and examples](https://github.com/diasbruno/verona)
to get started. The compiler is implemented in Common Lisp, with editor support
for Emacs and SLIME.
