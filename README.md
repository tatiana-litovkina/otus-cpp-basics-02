# OTUS C++ Basics — Homework 02

Домашнее задание 2: настройка локального окружения и разделение функции `todo_move_me_out` на отдельные файлы.

## Что сделано

- Функция `todo_move_me_out` вынесена из `hello_world.cpp` в отдельные файлы:
  - `move_me_out.h` — объявление
  - `move_me_out.cpp` — реализация
- В `hello_world.cpp` добавлен `#include "move_me_out.h"`
- В `CMakeLists.txt` добавлены оба новых файла
- Функция `main` не изменялась
- Проект собирается через CMake

## Схема локальной сборки

- ОС: macOS
- IDE: Visual Studio Code
- Компилятор: Apple Clang (Xcode Command Line Tools)
- Система сборки: CMake

## Сборка

```bash
mkdir build
cd build
cmake ..
cmake --build .
./hello_world
```
