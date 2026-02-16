[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22653425)
# C++ Compilation Pipeline Demonstration

## Objective
Demonstrate, using terminal commands and generated files, that C++ is a compiled language.

---

## 1. Source Code
File: `src/main.cpp`

---

## 2. Compilation Step
Command used:

```bash
g++ -c src/main.cpp -o build/main.o

## 3. Paso de Enlace (Linking)

Comando utilizado:

```bash
g++ build/main.o -o build/programa

