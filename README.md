# neutrino
Neutrino Recreational Programming Language

Neutrino is a golfing language inspired by Seriously/Actually and Jelly, as well as Enlist (also created by HyperNeutrino), which Neutrino is designed to replace.

Credit goes to Adam and Mr. Xcoder for helping with the ideas behind the functions for the language.

Usage: `./neutrino <filename> <args...>`

Command Line Flags:

- `-n` or `--native`: use native Python number types instead of `sympy`. Only use this option where timing is an issue (`sympy` can take quite a while to load) or when `sympy` is not available as this flag may cause some functions to behave unexpectedly and leads to floating point imprecision.
- `--test`: run test cases to ensure that the language is currently working
