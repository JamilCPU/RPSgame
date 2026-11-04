# RPSgame

A console Rock-Paper-Scissors game in C++. You type rock, paper or scissors, the computer picks randomly, the winner is announced, and the game tracks your total wins and current win streak across rounds until you decline to play again.

## Stack

- C++ (standard library only; `std::string`, `<iostream>`, `<cstdlib>`)

## Running

`main.cpp` includes `rockpaperscissors.cpp` directly, so compile `main.cpp` alone. The code uses the Windows-specific `_sleep` call, so build with MinGW/GCC or MSVC on Windows.

```
g++ main.cpp -o rps
./rps
```

## Project layout

- `main.cpp` - game loop
- `rockpaperscissors.h` - `draw` class declaration
- `rockpaperscissors.cpp` - CPU draw, input handling, win comparison and streak tracking

## Status

Early practice project, not under development. There are no tests.
