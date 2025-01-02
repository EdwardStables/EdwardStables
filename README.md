### Hi there!

I'm Ed, a hardware engineer working at Innosilicon developing GPU texture processing hardware and internal tooling. This page links to some of my personal projects.

## VPU (Voxel Processing Unit)

A just-for-fun voxel based display processor. This encompasses a hardware simulation (C++), hardware design (SystemVerilog), high level algorithm test platform (Zig), DSL compiler (Zig), and various python scripts to tie everything together.

- The hardware definitions, test programs, and assembler are found [here](https://github.com/EdwardStables/VPU_ASM).
- The C++ simulation of the hardware is [here](https://github.com/EdwardStables/VPU_Model).
- A real-time simulator debugger is [here](https://github.com/EdwardStables/VPU_Inspector), written in C++ and communicating with the simulator using gRPC to monitor the framebuffer and step the simulation.

The hardware design and compiler won't be made public until they're at least partially usable.

This also includes a [VGA driver](https://github.com/EdwardStables/VGA_Driver) design. I put this together for fun a while ago, but only recently resurrected it for this VPU project. Currently this just sends some hard-coded text output to a 1280x1024 VGA display. It's also acting as a test-bed for accessing RAM on the FPGA board.

## Wave View and VCD Parser

I've never gotten on well with GTKWave, so decided to make [my own wave viewer](https://github.com/EdwardStables/WaveViewer). For rendering this uses the fantastic [olcPixelGameEngine](https://github.com/OneLoneCoder/olcPixelGameEngine), and has a custom [VCD parser](https://github.com/EdwardStables/vcd_parser) using ANTLR. This has lua-based scripting using [sol3](https://github.com/ThePhD/sol2), but this isn't in the public version yet. Eventually this will be embedded into a proper GUI framework and become more than just a toy.

## Smaller Highlights

### Game Jams
I'm not good at making games, but I do enjoy the occasional jam. These are all implemented in C++ using the olcPixelGameEngine, and my own library of utilities and extensions.
- [Drowning Isn't Fun](https://themeaningofluff.itch.io/drowning-isnt-fun). OneLoneCoder 2024 Code Jam Entry. My first game jam entry that is actually somewhat fun to play, if not well balanced.
- [Don't Crash!](https://themeaningofluff.itch.io/dont-crash). OneLoneCoder 2023 Code Jam Entry. Avoided the bugs, but forgot to add very much gameplay.
- [The Recycling Button](https://themeaningofluff.itch.io/the-recycling-button). GMTK 2023 Game Jam Entry. I was very squeezed for time on this one, but was pleased to get the very basics of a factory game in there.
- [The Weather Garden](https://themeaningofluff.itch.io/the-weather-garden). OneLoneCoder 2022 Code Jam Entry. Unfinished and buggy, but lots of fun to make.

### Random Stuff
- [Advent of Code](https://github.com/EdwardStables/AoC). Solutions and test harness. Implemented in Python and Zig.
- [Software raytracer](https://github.com/EdwardStables/julia_ray_tracing). A Julia implementation of The Ray Tracer Challenge.

### University
A few interesting highlights:
- [High performance derivative free numerical optimisation](https://github.com/ImperialCollegeLondon/DirectSearch.jl). My final year university project. 
- [STUART](https://github.com/EdwardStables/STUART). A very enjoyable university final year group project, a robot designed to test human/machine interaction.
