# ☕ Java GUI Mini‑Suite (NetBeans Projects)

[![Java](https://img.shields.io/badge/Java-Swing-orange)](#)
[![IDE](https://img.shields.io/badge/IDE-Apache%20NetBeans-blue)](#)
[![Apps](https://img.shields.io/badge/Projects-3%20Mini%20Apps-green)](#)
[![Build](https://img.shields.io/badge/Build-JAR%20Files-purple)](#)
[![Focus](https://img.shields.io/badge/Focus-GUI%20%26%20Event%20Handling-lightgrey)](#)

A small collection of **three Java Swing desktop apps** built in **Apache NetBeans IDE 16**:

- 🎮 **Cross N Knot** - Tic‑Tac‑Toe game
- 🧮 **SI Calculator** - standard arithmetic calculator
- 🔬 **Scientific Calculator** - extra math functions

> **Tip:** The easiest way to run these is via **NetBeans** (projects are already configured).

---

## 📦 Projects

| Project | What it is | Run in NetBeans | Run as JAR |
|---|---|---:|---:|
| `CrossNKnot` | Tic‑Tac‑Toe (X/O) | ✅ | ✅ |
| `siCalculator` | Standard calculator | ✅ | ✅ |
| `simpleScientificCalculator` | Scientific calculator | ✅ | ✅ |

---

## ✅ Requirements

- **Java JDK 8+**
- **Apache NetBeans IDE 16** (recommended)
- (Optional) **Ant** (NetBeans can run Ant projects automatically)

---

## 🚀 Quick Start (NetBeans)

1. Download / clone this repository
2. Open **Apache NetBeans**
3. Go to **File → Open Project**
4. Open any of these folders:
   - `CrossNKnot`
   - `siCalculator`
   - `simpleScientificCalculator`
5. Right‑click the project → **Run**

NetBeans will use the project configuration to locate the correct **Main Class**.

---

## ▶ Run the prebuilt JAR (no IDE)

You can find the jar file in each project’s `Jar File/` folder, you can run them directly:

```bash
# Windows / macOS / Linux (same command)
java -jar CrossNKnot.jar
java -jar siCalculator.jar
java -jar simpleScientificCalculator.jar
```

> If double‑clicking the JAR doesn’t work on Windows, run it from **Command Prompt** so you can see any error output.

---

## 🧱 Build your own JAR (NetBeans)

For any project:
1. Right‑click the project → **Clean and Build**
2. NetBeans generates output in that project’s `dist/` folder (common default)

