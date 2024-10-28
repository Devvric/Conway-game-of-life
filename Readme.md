Executable download: https://github.com/Devvric/Conway-game-of-life/blob/patch/Conway%20Game%20Of%20Life.zip

<img src="https://i.imgur.com/JFX9qQE.png">

Console arguments: (use '.' to use default value)
--

1. Screen width
2. Screen height
3. Screen update delay (ms)
4. Spawn probability (0-100) [at first frame of the game]
5. Cell pixel side length (>0)

- Sample: `conway.exe 1000 500 10 70 1` (100x500 window, 10ms delay, 70% chance of spawning at first frame, with cells of 1 pixel of side size)
- Sample: `conway.exe . . . 50 4` (default window size, default delay, 50% chance of spawning at first frame, with cells of 4 pixels of side size)


Controls:
--

- ESCAPE, Q: Quit
- P: Pause / Resume 
- Up arrow: Speed up
- Down arrow: Slow down
- Mouse left click and drop: Add live cells
- Mouse right click and drop: Kill cells


Fork Author Notes:
--

Forked away because it did not work straight out because of the broken SDL dependencies. Repaired them. It should be able to compile with .sln in Visual Studio.
A pre-compiled release for x64 is located in the x64 folder.
