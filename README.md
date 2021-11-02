# Simulation of particles going through a reaction

A very simple simulation to get a feel for how particles from an initially
homogeneous population desynchronize as they progress through a multi-step
reaction. Lots of simplifying assumptions, read notebook for details.

## Preview notebook

You can read an HTML export of the notebook
[here](https://guillawme.github.io/reaction-progress-simulation/reaction-progress-simulation.jl.html).

## How to run

This requires [Julia](https://julialang.org/) and
[Pluto.jl](https://github.com/fonsp/Pluto.jl). Once you have both installed,
simply run the following commands:

``` sh
$ cd /path/to/this/repo
$ julia
```

Then, in Julia:

``` julia
julia> using Pluto
julia> Pluto.run()
```

Finally, in Pluto, paste the name of the notebook file
`reaction-progress-simulation.jl` in the "open notebook" field.

