![SFML image](https://img.shields.io/badge/-white?style=for-the-badge&logo=SFML&logoColor=8CC445)
<img src="cpp_logo.png" height="22">
# Kronos Time Clock
- Create Kronos Time Clock: using Regular Expression Parsing to verify device boot up timing.

## Features:
- First parse log file, then storing information from parsing, write the line output file.

## To Set Up:
- Git clone repository.
- Set SFML environment:
[SFML](https://www.sfml-dev.org/)
- On Mac use `brew install sfml`
- Run `brew info sfml`   tofind where is sfml locate. My SFML is `"opt/homebrew/Cellar/sfml/2.5.1_2"`. Use flag` -I` and `-L` for  `include`and `lib`.
- Install boost
  - `brew install boost`
  - `brew info boost`. My boost version is `/opt/homebrew/Cellar/boost/1.81.0_1`
- Run `g++ -g -std=c++0x kronos.cpp -I/opt/homebrew/Cellar/sfml/2.5.1_2/include -L/opt/homebrew/Cellar/sfml/2.5.1_2/lib -I/opt/homebrew/Cellar/boost/1.81.0_1/include -L/opt/homebrew/Cellar/boost/1.81.0_1/lib -o  Kronos -lsfml-graphics -lsfml-window -lsfml-system -lboost_regex -lboost_date_time -lboost_unit_test_framework`

## Author
- `William Vo`
## Technologies used:
-`C++`
- `SFML`: `Graphics, System, Window`
- `Boost`:` regex, date/time, and unit test framework`



