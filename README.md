# BeamLimitingDevicePlots.jl

A package to plot beam-limiting devices using in external beam radiotherapy.
It plots beam-limiting devices as defined in [DoseCalculations.jl](https://github.com/ACRF-Image-X-Institute/DoseCalculations.jl).

![Aperture Example](examples/aperture.png)

## Installation

1. Navigate to your project
2. Open the Julia REPL
3. *[Optional]* Activate a new environment
4. Enter package mode by typing `]`
5. Install using 
    ```julia
    add https://github.com/lmejn/BeamLimitingDevicePlots.jl
    ```

## Usage

Import the package using,
```julia
using BeamLimitingDevicePlots
```

The two main function are:
```julia
plot_bld(args...; kwargs...)
```
To plot the geometry of beam-limiting devices. Currently supported devices are:

- Multi-Leaf Collimator
- Jaws

```julia
axes_lims!(args...; kwargs...)
```
To set the axes limits of the figure based on the geometry of the beam-limiting device.

See the example [notebook](https://github.com/lmejn/BeamLimitingDevicePlots.jl/blob/4ca901f4741e06ab698532a4a402d99430de3eef/examples/Plotting%20Beam%20Limiting%20Devices.ipynb) for usage.


