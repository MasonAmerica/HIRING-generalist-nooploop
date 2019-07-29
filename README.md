Mason Engineering - Generalist Engineer exercise
===

# Noop Looping Command

Your objective is to write a simple command-line tool named `nooploop` in one of the languages
shown below. When run, this tool will simply print `Waiting for keypress` once every second, but
prints `Done!` and quits back immediately to the invoking shell as soon any key on the keyboard
is pressed.

## Example

For instance, a run of the program may look like this:

```bash
nooploop
Waiting for keypress
(one second passes)
Waiting for keypress
(one second passes)
:
:
Waiting for keypress
(user presses <Enter>)
Done.
```

# Addon 1
If you reach this stage, add a command line parameter `-n <sec>` to accept as input the number
of seconds between pauses.

## Example

For instance, a run of this enhanced program may look like this:

```bash
nooploop -n 2
Waiting for keypress
(two seconds pass)
Waiting for keypress
(two seconds pass)
:
:
Waiting for keypress
(one second passes)
(user presses <Enter>)
Done.
```

# Addon 2
If you reach this stage, enhance your program to print out upon a keypress, the number of seconds
remaining (up to 2 decimal points of precision) before it would print `Waiting for keypress` again.

## Example

For instance, a run of this enhanced program may look like this:

```bash
nooploop -n 5
Waiting for keypress
(five seconds pass)
:
:
Waiting for keypress
(just over one second passes)
(user presses <Enter>)
Done, with 3.89 seconds to go.
```

# Submission

You are to build a small program that can be run from the command line as described above.

## DOs
* Fork this repo to your own user space, make it private (now possible with free accounts
  as well), and add @scorpiodawg as an outside collaborator
* Push all changes to the `master` branch of your fork when your time is up. Do not worry
  about incomplete work -- different engineers take different lengths of time and this will
  be accounted for. We will then fork your repo and review your code.
* Use one of the following languages/tools for the exercise:
  * Golang
  * Javascript with NodeJS/TypeScript
  * C/C++
  * Python 2 or 3
  * Java
  * Kotlin
  
  If you wish to use one of the languages not in this list, please chat with your interviewer first.
* Do include a `NOTES.md` with any notes worth sharing such as build instructions, and if possible, any
  _significant_ resources used during development (StackOverflow questions, articles, sites, etc. 
  You do not need to include links to questions about language syntax, for e.g.)

## DONTs
- Don't jump right in if you have any doubts as to whether your choice of language/
  framework might not be suitable for our review (e.g. less common ones such as 
  Clojure, Fortran, Elixir, etc.). Please clarify with your interviewer first.

**All the best!**
