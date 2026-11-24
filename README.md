# DoubleArrayTries

<!-- wardjm-fork-note -->
> [!NOTE]
> **This is a maintained fork of [chengchingwen/DoubleArrayTries.jl](https://github.com/chengchingwen/DoubleArrayTries.jl).** The upstream package is no longer
> actively updated, so I'm keeping this fork working with current Julia and current versions of its
> dependencies (StringViews 2). The fork keeps the original package name and UUID but is not
> registered in General, so install it by URL:
>
> ```julia
> using Pkg
> Pkg.add(url = "https://github.com/wardjm/DoubleArrayTries.jl")
> ```
>
> Issues and pull requests are welcome on this fork.


[![Stable](https://img.shields.io/badge/docs-stable-blue.svg)](https://chengchingwen.github.io/DoubleArrayTries.jl/stable/)
[![Dev](https://img.shields.io/badge/docs-dev-blue.svg)](https://chengchingwen.github.io/DoubleArrayTries.jl/dev/)
[![Build Status](https://github.com/chengchingwen/DoubleArrayTries.jl/actions/workflows/CI.yml/badge.svg?branch=main)](https://github.com/chengchingwen/DoubleArrayTries.jl/actions/workflows/CI.yml?query=branch%3Amain)
[![Coverage](https://codecov.io/gh/chengchingwen/DoubleArrayTries.jl/branch/main/graph/badge.svg)](https://codecov.io/gh/chengchingwen/DoubleArrayTries.jl)


A pure Julia implementation of Double Array Trie. This is basically a minimal direct translation of the [xcdat library](https://github.com/kampersanda/xcdat). See their [amazing paper](https://kampersanda.github.io/pdf/KAIS2017.pdf) for detailed explanation.
