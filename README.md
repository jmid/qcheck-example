qcheck-example
==============

This provides a minimal example of [QCheck](https://github.com/c-cube/qcheck/) (>=0.5), ocamlfind, and ocamlbuild. 

Beware that QCheck's API changed with the 0.5 release. As a
consequence this example will not compile with earlier versions.

To enable type feedback in an IDE, the `.merlin` file informs [merlin](https://github.com/ocaml/merlin) (an OCaml editor service/server) that the source code requires the `qcheck` package.
