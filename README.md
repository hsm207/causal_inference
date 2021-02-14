# Introduction
 This repo contains my attempt at most of the study questions in the `Causal Inference: A Primer` book.

 # Usage
 Run the notebooks inside a container defined by the [compbox](https://github.com/hsm207/compbox) image.

To install the Julia dependencies, open a terminal in the project's root folder and execute:
```
julia --project=. -e 'using Pkg; Pkg.instantiate()'
```

To run the Jupyter notebook server, run:
```bash
jupyter notebook --ip 0.0.0.0 --no-browser
```
