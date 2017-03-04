# gemm_example

Removing gsl from dependencies in dub.json can only successfully compile the program.

Compile using ldmd2:

```sh
dub build --compiler=ldmd2 --parallel --force
```
