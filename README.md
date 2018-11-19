# Explore BuckleScript compiler-libs alternative approach

Exploration to be able to expose OCaml `compiler-libs` modules in a BuckleScript project.

:warning: The project compiles but has not been tested thoroughly (or at all) yet.

The `compiler-libs` modules are exposed by including `node-modules/bs-platform` paths in `bsconfig`. Due to `config.mlp` requiring some pre-processing, for not `config.ml` and `config.mli` are vendored in `vendor/ocaml`.

See https://reasonml.chat/t/ocaml-migrate-parsetree-for-bucklescript/1034 for further discussion.

# Build
```
yarn install
yarn build
```
