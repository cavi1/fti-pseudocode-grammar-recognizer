# fti-pseudocode-grammar-recognizer

*Español abajo / English below*

---

## 🇪🇸 Español

### Descripción

Trabajo final grupal (Grupo N°4) de la materia **Fundamentos Teóricos de la Informática** — UNPSJB. Implementa un **reconocedor de gramática para pseudocódigo** mediante un **Autómata Finito No Determinista (AFND)**, junto con su modelado formal en JFLAP.

El autómata reconoce un lenguaje de pseudocódigo con estructuras de lectura/escritura, asignaciones, condicionales (`si/entonces/sino/finsi`), bucles `mientras` y `repetir/hastaque`, incluyendo un nivel de anidamiento entre estructuras.

### Tecnologías

- Python (implementación del autómata)
- JFLAP (modelado formal del AFND)
- Casos de prueba en texto plano (~20 ejemplos, válidos e inválidos)

### Qué incluye

- Definición formal de 25 estados y sus transiciones, siguiendo la gramática del pseudocódigo.
- Reconocimiento de estructuras simples y anidadas (un nivel): `if` dentro de `while`, `while` dentro de `if`, `if/else` dentro de `while`.
- Soporte para variantes de escritura (minúsculas y PascalCase) de las palabras clave.
- Suite de más de 50 pruebas automáticas embebidas en el código, cubriendo casos válidos e inválidos (errores de sintaxis: falta de punto y coma, variables no declaradas, estructuras incompletas, orden incorrecto, etc.).
- Modo interactivo por consola y modo de procesamiento de archivos `.txt`.

### Mi contribución (Cavi)

Trabajo en equipo (grupo de 4) — mi parte específica fue la **implementación completa del reconocedor en Python**:

- Escritura y refinamiento iterativo del autómata en código (9 de los 11 commits del repositorio corresponden a esta implementación y sus mejoras sucesivas).
- Diseño de la suite de pruebas automáticas, cubriendo tanto cadenas aceptadas como una amplia variedad de casos inválidos para validar la robustez de la gramática.
- Manejo de variantes de sintaxis (minúsculas y PascalCase) para mayor flexibilidad del reconocedor.

El modelado del autómata en JFLAP fue aporte de mi compañero de equipo.

### Cómo correrlo

```bash
python reconocedor_gramatica_pseudocodigo_FTI_2025.py
```

---

## 🇬🇧 English

### Description

Group final project (Team N°4) for the **Theoretical Foundations of Computer Science** course — UNPSJB. Implements a **pseudocode grammar recognizer** using a **Non-deterministic Finite Automaton (NFA)**, along with its formal modeling in JFLAP.

The automaton recognizes a pseudocode language with read/write structures, assignments, conditionals (`if/then/else/endif`), `while` loops, and `repeat/until` loops, including one level of nesting between structures.

### Tech stack

- Python (automaton implementation)
- JFLAP (formal NFA modeling)
- Plain-text test cases (~20 examples, valid and invalid)

### What it includes

- Formal definition of 25 states and their transitions, following the pseudocode grammar.
- Recognition of simple and nested (one level) structures: `if` inside `while`, `while` inside `if`, `if/else` inside `while`.
- Support for keyword variants (lowercase and PascalCase).
- A suite of 50+ automated tests embedded in the code, covering valid and invalid cases (syntax errors: missing semicolons, undeclared variables, incomplete structures, incorrect ordering, etc.).
- Interactive console mode and `.txt` file-processing mode.

### My contribution (Cavi)

Team project (4 members) — my specific part was the **full implementation of the recognizer in Python**:

- Wrote and iteratively refined the automaton in code (9 of the repository's 11 commits correspond to this implementation and its successive improvements).
- Designed the automated test suite, covering both accepted strings and a wide range of invalid cases to validate the grammar's robustness.
- Handled syntax variants (lowercase and PascalCase) for added recognizer flexibility.

The JFLAP automaton modeling was contributed by my teammate.

### How to run

```bash
python reconocedor_gramatica_pseudocodigo_FTI_2025.py
```
