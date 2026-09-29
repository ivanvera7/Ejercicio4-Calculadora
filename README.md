<div align="center">

# 🧮 Ejercicio 4 — Calculadora en Java

**Las 4 operaciones básicas: suma, resta, multiplicación y división**

![Java](https://img.shields.io/badge/Java-Ejercicio_4-orange?style=for-the-badge&logo=openjdk&logoColor=white)
![Nivel](https://img.shields.io/badge/Nivel-Basico-brightgreen?style=for-the-badge)
![Dificultad](https://img.shields.io/badge/Dificultad-⭐_4/5-yellow?style=for-the-badge)

</div>

---

## 📖 Descripción

Este es el **Ejercicio 4** de mi serie de práctica en Java. Funciona como una
**calculadora simple**: toma dos números y calcula las **cuatro operaciones
aritméticas básicas** en una sola ejecución, mostrando cada resultado por
consola.

> 🎯 **Objetivo del ejercicio:** combinar los operadores `+`, `-`, `*` y `/`
> en un mismo programa, guardando cada resultado en su propia variable.

## ✨ Qué hace

```java
int numero1        = 20;
int numero2        = 5;
int suma           = numero1 + numero2;
int resta          = numero1 - numero2;
int multiplicacion = numero1 * numero2;
int division       = numero1 / numero2;
```

Imprime:

```
Numero1: 20
Numero2: 5
·························
Suma: 25
Resta: 15
Multiplicación: 100
División: 4
```

## 🧠 Conceptos practicados

| Concepto | Descripción |
|:--|:--|
| `+` Suma | `20 + 5 = 25` |
| `-` Resta | `20 - 5 = 15` |
| `*` Multiplicación | `20 × 5 = 100` |
| `/` División | `20 ÷ 5 = 4` |
| Varias variables | Un resultado distinto por operación |

> ⚠️ **Nota:** con `int`, la división descarta los decimales
> (ej: `7 / 2` sería `3`, no `3.5`). Para decimales se usa `double`.

## 🛠️ Requisitos

- **JDK 8** o superior ([Descargar JDK](https://adoptium.net/))
- Un editor: IntelliJ IDEA, VS Code o similar
- Terminal o símbolo del sistema

## ▶️ Cómo ejecutarlo

```bash
# 1. Compilar
javac src/Main.java

# 2. Ejecutar
java -cp src Main
```

O directamente desde **IntelliJ IDEA** → botón ▶ *Run*.

## 📂 Estructura del proyecto

```
Ejercicio4-Calculadora/
├── src/
│   └── Main.java      ← código fuente
├── .gitignore
└── README.md
```

## 🗺️ Ruta de aprendizaje

| # | Repositorio | Tema |
|:-:|:--|:--|
| 1 | [HolaMundo](https://github.com/ivan99vera1-wq/Ejercicio1-HolaMundo) | Primer programa, imprimir texto |
| 2 | [Ejercicio2-Variables](https://github.com/ivan99vera1-wq/Ejercicio2-Variables) | Variables y tipos de datos |
| 3 | [Ejercicio3-Sumar](https://github.com/ivan99vera1-wq/Ejercicio3-Sumar) | Operador suma |
| **4** | 🧮 **Ejercicio4-Calculadora** *(este)* | Las 4 operaciones básicas |

---

<div align="center">

📚 Ejercicio de práctica de Java · Hecho con ☕ por [ivan99vera1-wq](https://github.com/ivan99vera1-wq)

</div>
