<a name="en"></a>
![Outcome](images/outcome.png)
![Generator](images/Generator.png)

# 🖨️ BIOX G-code Generator via Rhino-Grasshopper

[![Language](https://img.shields.io/badge/Language-English%20%7C%20%E4%B8%AD%E6%96%87-blue.svg)](README_CN.md)

Welcome to the **Cellink-BIOX G-code Generator**!
This project, built on Rhino-Grasshopper, aims to directly generate executable, customized G-code for the **Cellink-BIOX bio-3D printer**.
This project supports the generation of the following five basic shapes:
- `Cube` — Array of cube
- `Cylinder` — Array of cylinder
- `Wave` — Array of wave
- `Hemisphere` — Array of hemisphere
- `Cone` — Array of cone

Through parametric design, you can freely define core parameters of the printed model, such as **size, infill density, positive and negative structure, spatial position, and printing speed**.
This project has designed two sets of code specifically for different versions of the BIOX printer software to ensure compatibility with different versions.

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
````
## ⭕️ Requirements
* Rhino 8
* Grasshopper
* Xylinus plugin    https://www.food4rhino.com/en/app/xylinus-novel-control-3d-printing
* Human UI plugin   https://www.food4rhino.com/en/app/human-ui

