# curses-test

This is a very simple cmake and ncurses test.

# pre-requisites
  1. cmake
  2. ninja-build
  3. ncurses
  
The exporting compile commands is only relevant for those who use clangd for language support.

```
git clone https://github.com/TeddyRandby/curses-test.git ./curses-test
cd curses-test
cmake . -DCMAKE_GENERATOR:INTERNAL=Ninja -DCMAKE_EXPORT_COMIPLE_COMMANDS=ON
ninja
./Test
```
