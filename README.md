# Raytracer Project

## Project Overview

This project is a raytracer implementation designed to render 3D scenes based on configuration files. It uses a modular architecture to separate concerns such as mathematical operations, scene parsing, and rendering primitives. The project is written in C++ and follows object-oriented principles.

<img width="1405" height="757" alt="image" src="https://github.com/user-attachments/assets/8be59d0f-479d-4e5e-ab7c-82957b3915c0" />


---

## Requirements

C++17 for filesystem

## Project Structure

Here is the directory tree of the project:


# Raytracer

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE)
[![Build Status](https://img.shields.io/badge/build-manual-orange)](#)

Raytracer is a modular C++ ray tracing engine that renders 3D scenes defined by simple configuration files. This repository contains the implementation, example scenes, and generated documentation — suitable for a professional portfolio and demonstration of architecture, parsing and rendering techniques.

Note: this project was developed as part of coursework at **EPITECH**.

---

Overview
- Rendering support for common primitives (sphere, plane, cylinder, cone).
- Simple material and light handling (ambient, directional, etc.).
- Scene parsing from configuration files and example scene sets.
- Clean, modular code organization (Math / Primitives / Materials / Scene / Utils).

---

Quick start

Prerequisites (Debian/Ubuntu):

```bash
sudo apt update
sudo apt install -y build-essential cmake libsfml-dev
```

Build (Make):

```bash
make
```

Build (CMake — recommended):

```bash
mkdir -p build && cd build
cmake ..
make
```

Run an example scene:

```bash
./raytracer scenes/mort.conf
```

---

Documentation
- Generated Doxygen documentation: `documentation/html/` (open `index.html`).
- Example scenes: `scenes/`.

---

Contributing
- To report an issue: open an issue on the repository.
- To contribute code: create a branch, open a pull request and add your name to `CONTRIBUTORS.md`.
- Keep contributions minimal and focused (small PRs, clear messages).

---

Credits
- Developed by a small team and several contributors. See [CONTRIBUTORS.md](./CONTRIBUTORS.md) for a general list of contributors.

---

License
This project is released under the MIT License — see `LICENSE` for details.

---

Key features
- Rendering of common primitives (sphere, plane, cylinder, cone, etc.).
- Materials and light handling (ambient, directional, ...).
- Scene parsing from configuration files.
- Modular architecture (Math / Primitives / Materials / Scene / Utils).

Technologies
- Language: C++ (C++17)
- Build system: Make / CMake

---

Quick install

Basic prerequisites (Debian/Ubuntu):

```
sudo apt update
sudo apt install -y build-essential cmake libsfml-dev
```

Build using Make (simple):

```
make
```

Build using CMake (recommended):

```
mkdir -p build && cd build
cmake ..
make
```

After building, the executable is available at the repository root (or in `build/` depending on your configuration). Example:

```
./raytracer scenes/mort.conf
```

---

Examples & documentation
- Generated documentation (Doxygen) is available in `documentation/html/`.
- Example scene files are available in the `scenes/` folder.

---

Contributing
- To report a bug or request an improvement: open an issue.
- To contribute code: create a branch, open a pull request, and add your name to `CONTRIBUTORS.md`.
- Please follow the project guidelines (formatting, simple tests, clear commit messages).

---

Credits & authors
- The project was developed by a small team. The contributors list is available in [CONTRIBUTORS.md](./CONTRIBUTORS.md).

---

License
This repository is licensed under the MIT License. See `LICENSE` for the full text.

---
```
