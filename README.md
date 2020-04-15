# Physics Test
A test of my custom physics engine written in C++ utilizing SDL2 for visualization.

# Technology
Written in C++ using custom rendering & physics enging utilizing SDL2 libraries.

# How to Play
Clone repository (or download repository as a .zip & extract) then run main.exe in the bin folder.

# Known Bugs
You can break the collision system by getting the ball up to too high a speed. The collision system does not use ray tracing, so if you can move fast enough that the next update calculates the ball past the wall, it will not register as a collision.
