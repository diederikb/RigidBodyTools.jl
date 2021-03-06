## RigidBodyTools.jl

_Tools for creating, moving, and discretizing rigid bodies_

| Documentation | Build Status |
|:---:|:---:|
|  [![docs](https://img.shields.io/badge/docs-latest-blue.svg)](https://JuliaIBPM.github.io/RigidBodyTools.jl/latest) | [![Build Status](https://travis-ci.com/JuliaIBPM/RigidBodyTools.jl.svg?branch=master)](https://travis-ci.com/JuliaIBPM/RigidBodyTools.jl) [![Build status](https://ci.appveyor.com/api/projects/status/6tokpjqb4x8999g0?svg=true)](https://ci.appveyor.com/project/JuliaIBPM/rigidbodytools-jl) [![codecov](https://codecov.io/gh/JuliaIBPM/RigidBodyTools.jl/branch/master/graph/badge.svg)](https://codecov.io/gh/JuliaIBPM/RigidBodyTools.jl) |

## About the package

The purpose of this package is to provide tools for rigid bodies with
point-discretized surfaces. It includes methods for

* a library of surface shape definitions and associated point discretizations
* calculation of geometric properties
* rigid-body motion and transformation of surface points
* collections of multiple rigid bodies

These tools support a variety of classes of problems, including those that involve bodies interacting with fluids, in which we would immerse these point-discretized representations into a computational grid.

<!--
Documentation can be found at https://JuliaIBPM.github.io/RigidBodyTools.jl/latest.

**RigidBodyTools.jl** is registered in the general Julia registry. To install, enter the package manager by typing
```julia
] add RigidBodyTools
```

Then, in any version, type
```julia
julia> using RigidBodyTools
```
For examples, consult the documentation or see the example Jupyter notebooks in the Examples folder.
-->
