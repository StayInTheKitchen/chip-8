# Chip-8 Emulator
play old games

![tetris](https://github.com/user-attachments/assets/d7f24333-76e7-4e3a-92e1-264c2d87158d)

## background
[](https://velog.io/@sitk/CHIP-8-emulator)

## how to build
``` bash
g++ src/*.cpp  -Iinclude -Llib -lmingw32 -lSDL2main -lSDL2 -o chip8.exe
```

## how to play
``` bash
chip8.exe <Scale> <Delay> <ROM>
```

- Scale: display scale
- Delay: game delay
- ROM: chip-8 game program path
