# OBCA
Optimization-Based Collision Avoidance - a path planner for autonomous parking

## How to run the code:

==== preparatory steps ===

1. Change to the directory

2. Install Julia from https://julialang.org/downloads/ (code tested on version 0.5) 

3. Open Julia in terminal

4. Install Julia package JuMP using Pkg.add("JuMP")

5. Install Julia package Ipopt using Pkg.add(“Ipopt”)

6. Install Julia package PyPlot using Pkg.add(“PyPlot”)


==== running the parking example ====

1. Start Julia in terminal

2. Type in terminal: include("setup.jl")

3. Type in terminal: include("main.jl")


==== modifying the code ====

1. To play with start points, change x0 in main.jl and run 
the code by include("main.jl")

2. If you change anything in one of the collision avoidance
problems, you need to activate the changes by running 
include("setup.jl")


Notice: this code has been tested on Julia 0.5, and might not run on any other Julia versions
