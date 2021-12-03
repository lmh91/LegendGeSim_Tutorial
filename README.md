# LegendGeSim.jl Tutorial

## 1) Clone the repo and enter the directory
```bash
git clone https://github.com/lmh91/LegendGeSim_Tutorial.git
cd LegendGeSim_Tutorial/
```

## 2) Enter the legend container

Depends on your setup.
## 3) Install the required packages and precompile them

```bash
julia -e 'using Pkg; pkg"registry add General https://github.com/legend-exp/LegendJuliaRegistry.git"'
julia --project=. -e 'using Pkg; pkg"instantiate; precompile"'
```

The package `IJulia.jl` needs to be installed and build in your
global default Julia Environment!

## 4) Create the notebook file

```bash
julia --project=. make.jl
```

## 5) Start the jupyter notebook (or lab)

```bash
juypyter lab
```