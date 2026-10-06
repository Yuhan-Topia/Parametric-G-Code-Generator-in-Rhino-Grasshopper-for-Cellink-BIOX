<a name="en"></a>
![Generator](images/Generator.png)

# 🖨️ BIOX G-code Generator via Rhino-Grasshopper

[![Language](https://img.shields.io/badge/Language-English%20%7C%20%E4%B8%AD%E6%96%87-blue.svg)](README_CN.md)

Welcome to the **BIOX G-code Generator** repository! This project provides a robust, parametric G-code generation tool built with Rhino-Grasshopper. It is specifically optimized for Direct Ink Writing (DIW) 3D printing of soft silicone materials and Carbon Nanotubes (CNTs) directly on **Cellink-BIOX** 3D printers. 

## ✨ Key Features
- **Parametric Design 📐**: Fully customizable parameters including size, infill density, positive/negative structures, print coordinates/positions, and dynamic print speeds.
- **Multiple Micro-Structures 🧊**: Generates toolpaths for various topological geometries: `Cube`, `Cylinder`, `Wave`, `Hemisphere`, `Cone`, and `Base`.
- **Dual Software Compatibility 🔄**: Includes two distinct sets of algorithms (`gcode` and `gcode2` folders) to ensure seamless compatibility with both software versions of the Cellink-BIOX printer.
- **Beginner-Friendly GUI 🖥️**: Features a dedicated file (`Cylinder_4_posi.gh`) utilizing the **Human UI** plugin. This provides an intuitive graphical interface, allowing new users to adjust parameters and generate G-code effortlessly without needing to navigate the complex Grasshopper node canvas.

## 📂 Repository Structure

```text
Parametric-G-Code-Generator-in-Rhino-Grasshopper-for-Cellink-BIOX
├── gcode/                  # Generators for BIOX software Version 1
│   ├── cube.gh
│   ├── wave.gh
│   ├── hemisphere.gh
│   ├── base.gh
│   ├── cylinder/           # Contains multiple iterative versions
│   └── cone/               # Contains multiple iterative versions
├── gcode2/                 # Generators for BIOX software Version 2
│   ├── cube.gh
│   ├── cylinder.gh
│   ├── wave.gh
│   ├── hemisphere.gh
│   └── base.gh
├── images/                 # Documentation assets
├── Cylinder_4_posi.gh      # 🌟 Human UI graphical interface (Best for beginners)
└── README.md               # You are here

## ⭕️ Requirements
Rhino 8
Grasshopper plugin
Xylinux plugin
Human UI plugin

![Outcome](images/outcome.png) 

