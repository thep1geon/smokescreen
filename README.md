# Smokescreen

'Smoke' for short

A reimplementation of Ruse with the idea of improving everything that went wrong
in Ruse. Ruse was more or less a cobbled together project in a days with little
regard for future maintance. Everything will be built up incrementally, starting
with the simplest Smoke program possible and slowly adding features.

Smoke aims to be more modular and even a library to embed into various C/C++ 
programs. Smoke will have a 'Smoke.h' acting as it's public API and the rest
will be modularized into several subsystems. This is in stark contrast to the
single-file mess that Ruse was, which made it increasingly harder to keep everything
separate from eachother towards the end; everything was too tightly coupled together.

Smoke is my next attempt at making a language that can actually be used for
real-world applications and projects. I have many future ideas having to do
with Smoke, such as an LSP, custom colorscheme through treesitter, and bindings
for some popular C libraries.

## Example

```Scheme
(= (* (+ 3 4) (/ 24 8)) 21)
```

^
That expression would evaluate to true.

## Language TODOs

- [ ] All of Ruse's core

- [ ] C Interop

- [ ] A better type system
    - [ ] user defined types

- [ ] Run on a VM instead of a tree-walk interpreter

- [ ] Macro system

- [ ] Garbage collector

- [ ] Tail-call optimization

- [ ] Embeddable

- [ ] Extenible from C
    - [ ] The ability to write C libraries that can be used in Smokes

## Future TODOs

For testing the language and such

- [ ] Open a file, write to it, and then close it

- [ ] Make a pong game
    - [ ] Write some Raylib bindings

- [ ] Advent of Code 2024

- [ ] Smoke subset written in Smoke
