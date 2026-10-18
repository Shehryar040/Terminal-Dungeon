cmake_minimum_required(VERSION 3.16)

project(TerminalDungeon
    VERSION 1.0
    LANGUAGES CXX
)

set(CMAKE_CXX_STANDARD 17)
set(CMAKE_CXX_STANDARD_REQUIRED ON)

add_executable(TerminalDungeon
    src/main.cpp
    src/Game.cpp
    src/Player.cpp
    src/Enemy.cpp
    src/Item.cpp
    src/Room.cpp
    src/SaveSystem.cpp
)

target_include_directories(TerminalDungeon
    PRIVATE
        include
)