
---

### ② `README_CN.md`（中文版）

```markdown
![Generator](images/Generator.png)

# 🖨️ BIOX G-code Generator：基于 Rhino-Grasshopper 的 G-code 生成器

[🇬🇧 English](README.md)

欢迎来到 **BIOX G-code Generator** 项目！

本项目基于 **Rhino-Grasshopper** 开发，是一个参数化 G-code 生成工具，专门针对 **Cellink-BIOX 3D 打印机**上的直接墨水书写（Direct Ink Writing, DIW）3D 打印进行优化，可用于软硅胶材料以及碳纳米管（CNTs）的打印。

## ✨ 主要功能

- **参数化设计 📐**：支持对打印尺寸、填充密度、正/负结构、打印坐标/位置以及动态打印速度等参数进行灵活调整。

- **多种微结构 🧊**：支持生成多种拓扑结构的打印路径，包括 `Cube`（立方体）、`Cylinder`（圆柱体）、`Wave`（波浪）、`Hemisphere`（半球）、`Cone`（圆锥）以及 `Base`（基底）。

- **双软件版本兼容 🔄**：项目包含两套不同的算法（`gcode` 和 `gcode2` 文件夹），分别适配不同版本的 Cellink-BIOX 打印机软件。

- **适合初学者的 GUI 🖥️**：提供专门的 `Cylinder_4_posi.gh` 文件，并使用 **Human UI** 插件构建图形化操作界面。即使不熟悉 Grasshopper 复杂的节点画布，初学者也可以通过直观的界面调整参数并生成 G-code。

## 📂 仓库结构

```text
Parametric-G-Code-Generator-in-Rhino-Grasshopper-for-Cellink-BIOX
├── gcode/                  # BIOX 软件版本 1 的 G-code 生成器
│   ├── cube.gh
│   ├── wave.gh
│   ├── hemisphere.gh
│   ├── base.gh
│   ├── cylinder/           # 包含多个迭代版本
│   └── cone/               # 包含多个迭代版本
├── gcode2/                 # BIOX 软件版本 2 的 G-code 生成器
│   ├── cube.gh
│   ├── cylinder.gh
│   ├── wave.gh
│   ├── hemisphere.gh
│   └── base.gh
├── images/                 # 项目图片及文档素材
├── Cylinder_4_posi.gh      # 🌟 Human UI 图形化界面（推荐初学者使用）
├── README.md               # 英文说明文档
└── README_CN.md            # 中文说明文档

## ⭕️ Requirements
Rhino 8
Grasshopper plugin
Xylinux plugin
Human UI plugin
