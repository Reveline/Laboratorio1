# TDA Exercises - C Educational Project

## Overview
A C-based educational project focused on implementing Abstract Data Types (TDAs) — specifically Lists and Stacks. Students implement functions in `exercises.c` and run a test suite to verify their solutions.

## Tech Stack
- **Language:** C (compiled with `gcc`)
- **Build:** Shell script (`test.sh`) that compiles and runs tests
- **No web frontend or backend server**

## Project Structure
- `exercises.c` — Student implementations (main file to edit)
- `arraylist.c / arraylist.h` — List (ArrayList) TDA implementation
- `stack.h` — Stack TDA header (wraps List)
- `test.c` — Test runner source code
- `test.sh` — Compiles and runs tests, tracks progress via git
- `log` — Records test results

## Workflow
- **Start application**: runs `bash test.sh` (console output)
- Compiles with: `gcc -g test.c -Wall -Werror -o a.out`
- Tests are interactive; asks whether to push progress to GitHub

## Exercises
1. `crea_lista()` — Initialize list with integers 1-10
2. `sumaLista(List *L)` — Sum all elements in a list
3. `eliminaElementos(List *L, int elem)` — Remove all instances of an integer
4. `copia_pila(Stack *P1, Stack *P2)` — Copy stack contents preserving order
5. `parentesisBalanceados(char *cadena)` — Check balanced brackets using a stack
