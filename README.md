# Computing setup scripts for the LEGEND experiment

See the LEGEND wiki for detailed instructions.

## General

## Python

## Julia

Open a [Julia REPL](https://docs.julialang.org/en/v1/stdlib/REPL/)
(interactive console) and run

```julia
julia> include(download("https://raw.githubusercontent.com/legend-exp/legend-computing-setup/main/legend_julia_setup.jl"))
```

to set up (resp. configure) Julia for LEGEND.

The LEGEND Julia setup script can be run multiple times, it will only install
packages and set preferences if they're still missing.
