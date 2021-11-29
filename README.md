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
julia --project=. -e 'using Pkg; pkg"instantiate; precompile"'
```

## 4) Create the notebook file

```bash
julia --project=. make.jl
```

## 5) Start the jupyter notebook (or lab)

```bash
juypyter lab
```