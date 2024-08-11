### Hi there!

I'm Ed, a hardware engineer working at Innosilicon developing GPU technology. Here are some of my ongoing projects, these are slow going until I finish my masters but should pick up after that.

## VPU (Voxel Processing Unit)

A just-for-fun voxel based display processor for developing computer architecture and digital design skills. Still in an early stage developing system infrastructure.

Currently this includes a [set of scripts](https://github.com/EdwardStables/VPU_ASM) for generating ISA definitions, and a C++ [cycle-accurate](https://github.com/EdwardStables/VPU_Model) simulation of the RISC style management core, and the DMA unit. I'm slowly implementing this in SystemVerilog when time permits, but this is not public yet.

## Wave View and VCD Parser

I've never gotten on well with GTKWave, so decided to make [my own wave viewer](https://github.com/EdwardStables/WaveViewer). For rendering this uses the fantastic [olcPixelGameEngine](https://github.com/OneLoneCoder/olcPixelGameEngine), and has a custom [VCD parser](https://github.com/EdwardStables/vcd_parser) using ANTLR. This has lua-based scripting using [sol3](https://github.com/ThePhD/sol2), but this isn't in the public version yet. Eventually this will be embedded into a proper GUI framework and become more than just a toy.

## Smaller Highlights

### Game Jams
I'm not good at making games, but I do enjoy the occasional jam. These are all implemented in C++ using the olcPixelGameEngine, and my own library of utilities and extensions.
- [The Weather Garden](https://themeaningofluff.itch.io/the-weather-garden). OneLoneCoder 2022 Code Jam Entry. Unfinished and buggy, but lots of fun to make.
- [The Recycling Button](https://themeaningofluff.itch.io/the-recycling-button). GMTK 2023 Game Jam Entry. I was very squeezed for time on this one, but was pleased to get the very basics of a factory game in there.
- [Don't Crash!](https://themeaningofluff.itch.io/dont-crash). OneLoneCoder 2023 Code Jam Entry. Avoided the bugs, but forgot to add very much gameplay.

### Random code
- [Advent of Code](https://github.com/EdwardStables/AoC)
- [Software raytracer](https://github.com/EdwardStables/julia_ray_tracing). A Julia implementation of The Ray Tracer Challenge.

### University
A few interesting highlights.
- [High performance derivative free numerical optimisation](https://github.com/ImperialCollegeLondon/DirectSearch.jl). My final year university project. 
- [STUART](https://github.com/EdwardStables/STUART). A very enjoyable university final year group project, a robot designed to test human/machine interaction.
