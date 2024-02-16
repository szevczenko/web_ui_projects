Build test app
===============
Windows
---------------
1. Install msys: https://www.msys2.org/
2. Run after install ucrt64.exe
3. Download tools
```
pacman -S mingw-w64-ucrt-x86_64-gcc
pacman -S make
pacman -S mingw-w64-ucrt-x86_64-nodejs
```
4. Enter to project folder:
```
cd path_to_web_ui_projects/valve_controller
```
5. For build project run:
```
make
```
6. Run in console:
```
./build/example.exe
```
