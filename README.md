# Additional material for the lecture "Numerik gewöhnlicher Differentialgleichungen" (in German), winter term 2025/2026

[![License: MIT](https://img.shields.io/badge/License-MIT-success.svg)](https://opensource.org/licenses/MIT)

This repository contains additional lecture material for the course

> Numerik gewöhnlicher Differentialgleichungen (Wintersemester 2025/2026)

at Johannes Gutenberg University Mainz, Germany. Most material like
lecture notes, literature recommendations, and exercise sheets will
be provided via Moodle. This repository contains additional material
and numerical examples based on code.

To work with the material interactively, you need to install Julia
(see section below). Moreover, static preview versions of the examples
can be accessed from the
[website of this repo](https://ranocha.de/2025_NumODE/).


## Installation

The numerical examples are written in the programming language
[Julia](https://julialang.org). To use the material interactively,
you need to download and install Julia. Please follow the links and
instructions on the official website
https://julialang.org/downloads/
of the Julia programming language. The material for this course
is written for Julia v1.10 (v1.10.10 and newer).

The examples are provided in form of
[Pluto.jl](https://github.com/fonsp/Pluto.jl)
notebooks. To use them, you  need to install the Julia package
Pluto.jl via the Julia package manager. You can do so as described
on the [official Pluto.jl website](https://plutojl.org/) to install
a recent version of Pluto.jl. If you want to use exactly the same
version of Pluto.jl that was used to generate the notebooks, please
proceed as follows.

## Working from a terminal (e.g., Linux or macOS)

Open a terminal and run

```bash
julia -e 'import Pkg; Pkg.activate(pwd()); Pkg.instantiate(); import Pluto; Pluto.run()'
```

in this directory. A browser window should open where you can
open the Pluto notebook you want to use.

## Windows

You can double-click the `open_pluto.bat` file in this directory to start Pluto.
Alternatively, open the Julia REPL in this directory, e.g., by navigating to this 
directory in the Windows File Explorer and typing "julia" the address bar. A console
window should open. There, execute

```julia
import Pkg; Pkg.activate(pwd()); Pkg.instantiate(); import Pluto; Pluto.run()
```

in the Julia REPL. A browser window should open where you can
open the Pluto notebook you want to use.
