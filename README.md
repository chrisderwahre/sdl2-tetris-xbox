SDL2 Tetris
===========

Incomplete Tetris clone that needs to be cleaned up

How to Build
------------

1. Get dependencies `SDL2` and `SDL2_ttf`
2. `git clone https://github.com/aderosier/sdl2-tetris.git sdl2-tetris`
3. `cd sdl2-tetris`
4. `make`

Controls
--------

- Arrow left/right - Move left/right
- Arrow up, Z, X - Rotate
- Arrow down - Speed up
- Space - Drop
- Shift - Hold
- Enter - Pause

TODO
----

Guideline checklist http://tetris.wikia.com/wiki/Tetris_Guideline
- [x] Playfield size
- [x] Tetromino colors
- [x] Tetromino start locations
- [ ] The tetrominoes spawn horizontally and with their flat side pointed down
- [ ] Super Rotation System http://tetris.wikia.com/wiki/SRS
- [ ] Lock delay http://tetris.wikia.com/wiki/Infinity
- [ ] Standard mappings for computer keyboards
- [ ] http://tetris.wikia.com/wiki/Random_Generator
- [x] Hold piece
- [x] Ghost piece
- [x] Designated soft drop speed
- [x] Player may only level up by clearing lines or performing T-Spin
- [ ] The player tops out when a piece is spawned overlapping at least one block

- [x] Display of next-coming tetrominoes
- [ ] T-spins
- [ ] Rewarding of back to back chains
- [ ] Delayed Auto Shift http://tetris.wikia.com/wiki/DAS
