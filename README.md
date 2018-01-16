# PowerSchema

[![Build Status](https://travis-ci.org/jdlara-berkeley/PowerSchema.jl.svg?branch=master)](https://travis-ci.org/jdlara-berkeley/PowerSchema.jl)

[![Coverage Status](https://coveralls.io/repos/jdlara-berkeley/PowerSchema.jl/badge.svg?branch=master&service=github)](https://coveralls.io/github/jdlara-berkeley/PowerSchema.jl?branch=master)

[![codecov.io](http://codecov.io/github/jdlara-berkeley/PowerSchema.jl/coverage.svg?branch=master)](http://codecov.io/github/jdlara-berkeley/PowerSchema.jl?branch=master)

The code in this repository is the base data management code for the global power system analysis tools repository.

## Installation

This package is not yet registered. **Until it is, things may change. It is perfectly
usable but should not be considered stable**.

You can install it by typing

```julia
julia> Pkg.clone("https://github.com/NREL/PowerSchema.jl.git")
```
## Usage

Once installed, the `PowerSchema` package can by used by typing

```julia
using PowerSchema
```
## To do list

- Include inner constructors in the types 
- Generate testing code 
- Define more clearly the data structure for generators and loads 
- Define the structure for forecasting data