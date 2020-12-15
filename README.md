```sh
opam switch create 4.09.1+flambda
opam install dune
eval $(opam env)
dune build --profile=release
```
