# {{{PKG}}}

|                                 **Documentation**                                  |                                                                                                 **Build Status**                                                                                                 |                                        **Others**                                         |
| :--------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------: |
| [![Stable][docs-stable-img]][docs-stable-url] [![Dev][docs-dev-img]][docs-dev-url] | [![Build Status][gha-img]][gha-url] [![Build Status][appveyor-img]][appveyor-url] [![Build Status][cirrus-img]][cirrus-url] [![pipeline status][gitlab-img]][gitlab-url] [![Coverage][codecov-img]][codecov-url] | [![GitHub license][license-img]][license-url] [![Code Style: Blue][style-img]][style-url] |

[docs-stable-img]: https://img.shields.io/badge/docs-stable-blue.svg
[docs-stable-url]: https://{{{USER}}}.github.io/{{{PKG}}}.jl/stable
[docs-dev-img]: https://img.shields.io/badge/docs-dev-blue.svg
[docs-dev-url]: https://{{{USER}}}.github.io/{{{PKG}}}.jl/dev
[gha-img]: https://github.com/{{{USER}}}/{{{PKG}}}.jl/workflows/CI/badge.svg
[gha-url]: https://github.com/{{{USER}}}/{{{PKG}}}.jl/actions
[appveyor-img]: https://ci.appveyor.com/api/projects/status/github/{{{USER}}}/{{{PKG}}}.jl?svg=true
[appveyor-url]: https://ci.appveyor.com/project/singularitti/{{{PKG}}}-jl
[cirrus-img]: https://api.cirrus-ci.com/github/{{{USER}}}/{{{PKG}}}.jl.svg
[cirrus-url]: https://cirrus-ci.com/github/{{{USER}}}/{{{PKG}}}.jl
[gitlab-img]: https://gitlab.com/singularitti/{{{PKG}}}.jl/badges/{{{branch}}}/pipeline.svg
[gitlab-url]: https://gitlab.com/singularitti/{{{PKG}}}.jl/-/pipelines
[codecov-img]: https://codecov.io/gh/{{{USER}}}/{{{PKG}}}.jl/branch/{{{branch}}}/graph/badge.svg
[codecov-url]: https://codecov.io/gh/{{{USER}}}/{{{PKG}}}.jl
[license-img]: https://img.shields.io/github/license/{{{USER}}}/{{{PKG}}}.jl
[license-url]: https://github.com/{{{USER}}}/{{{PKG}}}.jl/blob/{{{branch}}}/LICENSE
[style-img]: https://img.shields.io/badge/code%20style-blue-4495d1.svg
[style-url]: https://github.com/invenia/BlueStyle

The code, which is [hosted on GitHub](https://github.com/{{{USER}}}/{{{PKG}}}.jl), is tested
using various continuous integration services for its validity.

This repository is created and maintained by
[@singularitti](https://github.com/singularitti), and contributions are highly welcome.

## Package Features



## Installation

The package can be installed with the Julia package manager.
From the Julia REPL, type `]` to enter the Pkg REPL mode and run:

```
pkg> add {{{PKG}}}
```

Or, equivalently, via the [`Pkg` API](https://pkgdocs.julialang.org/v1/getting-started/):

```julia
julia> import Pkg; Pkg.add("{{{PKG}}}")
```

## Documentation

- [**STABLE**][docs-stable-url] — **documentation of the most recently tagged version.**
- [**DEV**][docs-dev-url] — _documentation of the in-development version._

## Project status

The package is developed for and tested against Julia `v1.6` and above on Linux, macOS, and
Windows.

## Questions and contributions

You can post usage questions on
[our discussion page](https://github.com/{{{USER}}}/{{{PKG}}}.jl/discussions).

We welcome contributions, feature requests, and suggestions. If you encounter any problems,
please open an [issue](https://github.com/{{{USER}}}/{{{PKG}}}.jl/issues).
The [Contributing](@ref) page has
a few guidelines that should be followed when opening pull requests and contributing code.
