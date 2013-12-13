Overhaul in progress (see details in message)

# Refactoring

DOP, OOP and helpers all have been refactored, which means:

- a lot of changes in comments/code presentation
- moving of big code blocks
- architecture changes (functions split, variables added, etc) but not functional

OOP has been split in three:

- types: the default types
- class: the class factory
- method: the method/function factory

# Features

In addition to refactoring, some little features have been added for the occasion.

- helpers: several functions like iterating over objects, native toString abd hasOwnProperty, etc.

# Documentation

HUGE work in progress. Still incomplete, sometimes inconsistent, maybe cryptic, but highly improved.

# Packaging

Development dependencies:

- benchmark: as we will have to do benchmark at some points
- tester: my own testing library, very useful, a compromise between real tests and nothing
