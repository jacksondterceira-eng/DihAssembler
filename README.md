# DihAssembler

DihAssembler is a simple GUI disassembler and Python bytecode viewer.  
It uses **PyQt6** for the interface and **Capstone** for binary disassembly.

---

## Features
- Disassembles **Python files** (`.py`) into bytecode.
- Disassembles **PE executables** (`.exe`) and **ELF binaries**.
- Falls back to raw x86_64 disassembly if unknown.
- Retro **green-on-black** styled interface.

---

## Running (Source)
Install requirements:
```bash
pip install -r requirements.txt
