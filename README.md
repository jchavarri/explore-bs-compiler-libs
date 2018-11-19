# Explore BuckleScript compiler-libs alternative approach

Exploration to be able to expose OCaml `compiler-libs` modules in a BuckleScript project.

:warning: Right now the project does *not* compile, due to `clflags.ml` needing `config.ml`, but this file needs some pre-processing.

See https://reasonml.chat/t/ocaml-migrate-parsetree-for-bucklescript/1034 for further discussion.

# Build
```
yarn install
yarn build
```
