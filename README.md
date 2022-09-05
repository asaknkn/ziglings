# Ziglings

Welcome to Ziglings! This project contains a series of tiny broken programs.
By fixing them, you'll learn how to read and write
[Zig](https://ziglang.org/)
code.

Those tiny broken programs need your help! (You'll also save the planet from
evil aliens and help some friendly elephants stick together, which is very
sweet of you.)

This project was directly inspired by the brilliant and fun
[rustlings](https://github.com/rust-lang/rustlings)
project for the [Rust](https://www.rust-lang.org/) language.
Indirect inspiration comes from [Ruby Koans](http://rubykoans.com/)
and the Little LISPer/Little Schemer series of books.

## Intended Audience

This will probably be difficult if you've _never_ programmed before.
But no specific programming experience is required. And in particular,
you are _not_ expected to have any prior experience with "systems programming"
or a "systems" level language such as C.

Each exercise is self-contained and self-explained. However, you're encouraged
to also check out these Zig language resources for more detail:

* https://ziglearn.org/
* https://ziglang.org/documentation/master/

Also, the [Zig community](https://github.com/ziglang/zig/wiki/Community) is incredibly friendly and helpful!

## Getting Started

Install a [development build](https://ziglang.org/download/) of the Zig compiler.
(See the "master" section of the downloads page.)

Verify the installation and build number of `zig` like so:

```bash
$ zig version
0.10.0-dev.3685+xxxxxxxxx
```

Clone this repository with Git:

```bash
$ git clone https://github.com/ratfactor/ziglings
$ cd ziglings
```

Then run `zig build` and follow the instructions to begin!

```bash
$ zig build
```

## Advanced Usage

It can be handy to check just a single exercise or _start_ from a single
exercise:

```bash
zig build 19
zig build 19_start
```

You can also run without checking for correctness:

```bash
zig build 19_test
```

Or skip the build system entirely and interact directly with the compiler
if you're into that sort of thing:

```bash
zig run exercises/001_hello.zig
```

Calling all wizards: To prepare an executable for debugging, install it
to zig-cache/bin with:

```bash
zig build 19_install
```

## What's Covered

I've decide to limit Ziglings to the core language and not
attempt coverage of the Standard Library. Perhaps you can change
my mind?

Core Language

* [x] Hello world (main needs to be public)
* [x] Importing standard library
* [x] Assignment
* [ ] Arrays
* [ ] Strings
* [ ] If
* [ ] While
* [ ] For
* [ ] Functions
* [ ] Errors (error/try/catch/if-else-err)
* [ ] Defer (and errdefer)
* [ ] Switch
* [ ] Unreachable
* [ ] Enums
* [ ] Structs
* [ ] Pointers
* [ ] Optionals
* [ ] Struct methods
* [ ] Slices
* [ ] Many-item pointers
* [ ] Unions
* [ ] Numeric types (integers, floats)
* [ ] Labelled blocks and loops
* [ ] Loops as expressions
* [ ] Builtins
* [ ] Inline loops
* [ ] Comptime
* [ ] Sentinel termination
* [ ] Quoted identifiers @""
* [ ] Anonymous structs/tuples/lists
* [ ] Async <--- IN PROGRESS!

## Contributing

Contributions are very welcome! I'm writing this to teach myself and to create
the learning resource I wished for. There will be tons of room for improvement:

* Wording of explanations
* Idiomatic usage of Zig
* Maybe additional exercises?

Please see CONTRIBUTING.md in this repo for the full details.


