# Lua Benchmarks

Compare the performance of different Lua implementations

## Sample Results

Computer information:

```
Distro: Ubuntu 22.04 LTS
Kernel: 4.4.0-19041-Microsoft
CPU:    Intel(R) Core(TM) i5-10400F CPU @ 2.90GHz
```
![](https://raw.githubusercontent.com/learno/Lua-Benchmarks/master/results/speedup_lua54.png)

## Usage

```
usage: lua runbenchmarks.lua [options]
options:
    --nruns <n>      number of times that each test is executed (default = 3)
    --no-supress     don't supress error messages from tests
    --output <name>  name of the benchmark output
    --normalize      normalize the result based on the first binary
    --speedup        compute the speedup based on the first binary
    --no-plot        don't create the plot with gnuplot
    --help           show this message
```

