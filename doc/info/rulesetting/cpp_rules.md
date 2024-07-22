< [Back](/)

--- 
# Rules for Implamantat the C++ Modul
This are the Rules from the mandotoy [subjeckt file](../../PDF/cpp_00_modul_subject.pdf) 

## Compile
- use this flages `-Wall -Wextra -Werror`
- use flag `-std=c++98`

## Formatting 
- exercise folder like `ex00`, `ex01`, `..`
- class names must be wirten in `UpperCamelCase`
	- `ClassName.hpp` -- `hpp` --> Header file
	- `ClassName.tpp` -- `tpp` --> Template Implementation File file
	- `ClassName.cpp` -- `cpp` 
- Output must end by a `newline`
- Goodbye `Norminette`
- Each class should have his ohne header 
- Use [include guards](include_guards.md)

## Forbinden 
- no external libarys, no `C++11`, no `Boost libraries`, also forbbiden is `printf()`, `alloc()`, `free()`
- `namespace` and **friend keywords** forbidden

## Allowed 
- Standardt libarys in C++
- additional files if is needed

--- 
### Look also

**[Good Practiec](../rulesetting/cpp_good_practice.md)**
