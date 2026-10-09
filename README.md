# C++ Typing Tutor Game

A console typing game in C++. Random digits fall down the screen, and you type each one before it reaches the bottom.

## Features

- A new random digit (0-9) appears at a random position every second
- The digits are stored in a linked list
- Typing the right digit removes it and adds 10 points
- The game ends at 100 points, when a digit reaches the bottom, or when you press Esc
- Shows your score and number of hits

> Windows only: it uses `conio.h`, `Sleep()` and `system("cls")`.

## Tech stack

C++ (Windows console: `conio.h`, `Windows.h`)

## Getting started

```bash
git clone https://github.com/Matiz009/cpp-typing-tutor-game.git
cd cpp-typing-tutor-game
gcc "TypingTutor.cpp" -o TypingTutor && ./TypingTutor
```

## Project structure

```
TypingTutor.cpp   Source code
TypingTutor.exe   Old Windows build
```

## Author

**Mati ul Rehman** - [github.com/Matiz009](https://github.com/Matiz009)
