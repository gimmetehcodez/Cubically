# Note that many features of the language are currently not working properly as I am refactoring everything about the interpreter. Cubically itself is not being modified and anything that worked in the old interpreter will work in the new one. You can still use the old interpreter [here](http://cubically.tryitonline.net).

# Cubically [![Build Status](https://travis-ci.org/aaronryank/cubically.svg?branch=master)](https://travis-ci.org/aaronryank/cubically) [![Code Coverage](https://codecov.io/github/aaronryank/cubically/coverage.svg?branch=master)](https://codecov.io/github/aaronryank/cubically?branch=master)

Cubically is a [work-in-progress](//github.com/cubically) esoteric programming language built to be complex and painful, and to encourage users to extensively [study](//github.com/cubically/algorithms) Rubik's Cubes.

The most recent [version](//github.com/aaronryank/cubically/releases) of Cubically is [2.3](//github.com/aaronryank/cubically/releases/tag/v2.3).

# Interpreter

 - To build the interpreter, type `make`. This will generate the executable `cubically`.
 - To build the visualizer, type `make visualizer`. This will generate the executable `visualizer`.
 - To clean up the object files after building, type `make clean`.

The interpreter is used like so:

    Usage: cubically <flags> <file | string> <size>
    Flags: f | second argument is a file
           s | second argument is a string
           u | read file/string as UTF-8
           c | read file/string as Cubically SBCS
    <size> specifies the size of the memory cube. If blank, a 3x3x3 will be assumed.

As a 3x3x3 memory cube is standard, it will be used throughout the tutorial and examples in the [docs](//github.com/aaronryank/Cubically/wiki).

# How to use

To learn how to use Cubically, check out [the Wiki!](//github.com/aaronryank/Cubically/wiki) It contains up-to-date information about every part of the language. Sometimes.

If you need help on a specific point, or something is unclear, feel free to [open an issue](//github.com/aaronryank/Cubically/issues).
