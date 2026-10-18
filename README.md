# 🎮 Terminal Dungeon

A small command-line dungeon adventure game written in modern C++.

The project is designed as a beginner-friendly C++ game while following a clean, modular project structure.

## ✨ Features

- 🧙 Player system
- ⚔️ Enemy combat
- ❤️ Health system
- 🧪 Potion system
- 💰 Coin/reward system
- 🗺️ Random dungeon rooms
- 💾 Save-game system
- 🎯 Win and game-over conditions
- 🧱 Object-oriented C++ architecture
- 🔨 CMake build system

## 🛠️ Technologies

- C++
- C++17
- CMake
- Standard Library
- Git / GitHub

## 📁 Project Structure

```text
terminal-dungeon/
│
├── .github/
│   └── workflows/
│       └── build.yml
│
├── assets/
│   └── README.md
│
├── include/
│   ├── Enemy.h
│   ├── Game.h
│   ├── Item.h
│   ├── Player.h
│   ├── Room.h
│   └── SaveSystem.h
│
├── src/
│   ├── Enemy.cpp
│   ├── Game.cpp
│   ├── Item.cpp
│   ├── Player.cpp
│   ├── Room.cpp
│   ├── SaveSystem.cpp
│   └── main.cpp
│
├── saves/
│   └── .gitkeep
│
├── tests/
│   └── README.md
│
├── .gitignore
├── CMakeLists.txt
├── LICENSE
├── README.md
└── CHANGELOG.md
```

## 🚀 Build Instructions

### 1. Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/terminal-dungeon.git
cd terminal-dungeon
```

### 2. Create a build directory

```bash
mkdir build
cd build
```

### 3. Generate the build files

```bash
cmake ..
```

### 4. Compile

```bash
cmake --build .
```

### 5. Run

Linux/macOS:

```bash
./TerminalDungeon
```

Windows:

```bash
TerminalDungeon.exe
```

## 🎮 How to Play

Start the game and enter your player name.

You can then:

1. Explore the dungeon
2. Fight enemies
3. Use health potions
4. Collect coins
5. Save your progress
6. Reach the final room
7. Complete the dungeon

## 🧠 C++ Concepts Demonstrated

This project demonstrates:

- Classes
- Constructors
- Encapsulation
- Header/source separation
- Enums
- References
- `const` member functions
- Vectors and standard containers
- Random number generation
- File I/O
- Control flow
- CMake
- Modular project architecture

## 🔮 Future Improvements

Possible future features:

- Multiple enemy types
- Weapons
- Armor
- Boss battles
- Multiple dungeon levels
- Character classes
- Experience and leveling
- Inventory system
- Better save/load functionality
- Colored terminal output
- ASCII-art map
- Unit tests
- Sound effects

## 📜 License

This project is licensed under the MIT License.