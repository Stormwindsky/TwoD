# NOTICE

**ZEL (Zephyr Engine Launcher)**

This project is primarily licensed under the **MIT License** (see the `LICENSE.md` file for the full text). 

However, this software includes third-party components and dependencies that are governed by their own respective licenses. Below is a summary of these components and their licensing terms.

---

## 1. Primary License (This Project)
**Copyright (c) 2026 Stormwindsky**

This software is provided under the **MIT License**. For the full legal text and permissions, please refer to the `LICENSE.md` file included in this repository.

---

## 2. Third-Party Dependencies

### Tkinter (Python GUI Toolkit)
* **Project:** [Tkinter / Tcl/Tk](https://docs.python.org/3/library/tkinter.html)
* **License:** Python Software Foundation (PSF) License
* **Usage:** Used for the graphical user interface of the Zephyr Engine Launcher.
* **Note:** Requires the `python3-tk` system package on Linux systems.

### Pygame Library
* **Project:** [Pygame](https://www.pygame.org/)
* **License:** GNU LGPL version 2.1
* **Usage:** Used for window management, rendering, and event handling in `twod_engine.py`.

### Python Standard Library
* **Project:** Python (json, math, os, sys modules)
* **License:** Python Software Foundation (PSF) License
* **Usage:** Core logic, system operations, and settings serialization.

---

## 3. Algorithm Attributions

### HSV to RGB Conversion
The `hsv_to_rgb` implementation in `twod_engine.py` is a standard mathematical conversion based on the HSV color model. While the implementation is custom for this engine, the logic follows public domain color space conversion formulas used widely in the computer graphics community.

---

## How to attribute
If you redistribute this software, you must retain this `NOTICE` file and the original `LICENSE.md` file to comply with the attribution requirements of the MIT, PSF, and LGPL licenses.
