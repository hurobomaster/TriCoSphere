# TriCoSphere Hand - English Documentation

Welcome to the **TriCoSphere Hand** project! This is an innovative modular collaborative robotic hand design developed with SolidWorks for comprehensive 3D modeling.

---

## 📌 Project Information

- **Project Name**: TriCoSphere Hand
- **Version**: 1.0
- **Project Duration**: March 2025 - September 2025
- **Conference**: ICRA 2026 (Accepted)
- **Design Software**: SolidWorks 2024+
- **Last Updated**: February 2026

---

## 💡 Project Overview

TriCoSphere Hand is a high-precision, modular, and easy-to-assemble parallel manipulator system. Version 1.0 focuses on **proof-of-concept** and **functional testing** of the overall design. Optimization work is currently in progress. Thank you for your interest—please stay tuned for future updates!

**Key Features:**
- ✅ Modular design for easy assembly and maintenance
- ✅ High-precision parallel mechanism structure
- ✅ Comprehensive standard parts library
- ✅ Multi-format export support

---

## 📁 File Structure

```
TriCoSphere_hand/
├── TriCoSphere.SLDASM              # Main assembly
├── README.MD                       # Mixed language documentation
├── README_zh.MD                    # Chinese documentation
├── README_en.MD                    # English documentation
│
├── 共轴手装配体/                    # Hand mechanism components
│   ├── 单指节.SLDASM               # Finger module assembly
│   ├── 底座.SLDPRT                 # Main base
│   ├── 基准台座.SLDPRT             # Reference base
│   ├── 中指模块.SLDPRT             # Middle finger drive module
│   ├── 支架系列/                   # Brackets 1-4 (8 total)
│   ├── 连接件系列/                 # Connectors and links
│   ├── 腿部结构/                   # Leg structures and covers
│   ├── 指尖.SLDPRT                 # Fingertip gripper
│   └── standard/                   # Standard parts library
│       ├── 轴承系列                # Bearings (thrust, thin, flanged)
│       ├── 紧固件                  # Fasteners (bolts, nuts, plugs)
│       ├── 球体.SLDPRT             # Standard sphere
│       └── 驱动器部件              # Motors and drivers
│
├── STEP/                           # STEP format (universal CAD)
│   └── TriCoSphere.STEP            # Complete assembly export
│
└── STL/                            # 3D printing format (reserved)
```

---

## 🔧 File Format Guide

| Format | Extension | Purpose | Compatibility |
|--------|-----------|---------|----------------|
| SolidWorks Assembly | `.SLDASM` | View assembly relationships, design modifications | SolidWorks 2024+ |
| SolidWorks Part | `.SLDPRT` | Edit individual parts, adjust parameters | SolidWorks 2024+ |
| Standard CAD Format | `.STEP` | Cross-platform sharing, third-party software | Universal CAD software |
| 3D Printing Format | `.STL` | Slicing and 3D printing processing | Cura, PrusaSlicer, etc. |

---

## 📋 Parts List

### Main Structure
| Part Name | Quantity | Purpose |
|-----------|----------|---------|
| Base | 1 | Main support structure |
| Reference Base | 1 | Positioning reference |
| Brackets (1-4) | 8 | Mechanical skeleton |

### Connector Series
| Part Name | Filename | Purpose |
|-----------|----------|---------|
| Long Edge Connector | 长边件.SLDPRT | Long edge connection |
| Short Edge Connector | 短边连接.SLDPRT | Short edge connection |
| End Rod | 末端杆件.SLDPRT | End-effector actuator |
| End Rod (Short Version) | 末端杆件缩短版.SLDPRT | Space-constrained applications |

### Legs and Support
| Part Name | Quantity | Purpose |
|-----------|----------|---------|
| Long Legs | 2 | Primary support legs |
| Long Leg Cover | 1 | Leg protection |
| Short Leg | 1 | Secondary support |
| Short Edge Leg | 1 | Short-edge support |

### Finger Module
| Part Name | Type | Description |
|-----------|------|-------------|
| Finger Joint | Assembly | Basic finger unit |
| Middle Finger Module | Part | Middle finger actuation |
| Fingertip | Part | End-effector gripper |

### Standard Parts Library

**Bearings:**
- Thrust Ball Bearing (3-8-3.5)
- Ultra-thin Bearing
- Flanged Bearing (3-6-2.5)

**Fasteners:**
- M3 Socket Head Cap Bolt
- M3 & M2.5 Nuts and Plugs
- M2.5 Locking Nut

**Other:**
- Standard Sphere
- Drive Components (Motors, Controllers, etc.)

---

## 🚀 User Guide

### 1️⃣ View Complete Assembly
```
Steps:
1. Open TriCoSphere.SLDASM in SolidWorks
2. Navigate the assembly tree to view part relationships
3. Use rendering features to generate high-quality visualizations
```

### 2️⃣ Edit Individual Parts
```
Steps:
1. Open the desired .SLDPRT file from 共轴手装配体/ folder
2. Make parameter modifications or design adjustments
3. Save—the main assembly updates automatically
```

### 3️⃣ 3D Printing Workflow
```
Steps:
1. Select the part(s) to print
2. Export to STL format
3. Process using slicing software (e.g., Cura, PrusaSlicer)
4. Upload to 3D printer
```

### 4️⃣ Cross-Platform Sharing
```
Steps:
1. Use STEP/TriCoSphere.STEP file
2. Open in any CAD software supporting STEP format
3. Compatible with Fusion 360, FreeCAD, AutoCAD, etc.
```

---

## 🛠️ Required Software & Tools

**Essential:**
- SolidWorks 2024 or higher

**Recommended Tools:**
- **Cura** - 3D printing slicing software
- **PrusaSlicer** - High-performance slicing tool
- **Fusion 360** - Cross-platform CAD viewer/editor
- **FreeCAD** - Open-source CAD software

---

## 📝 Contribution Guidelines

To contribute improvements and optimizations to the design:

1. **Edit Parts**: Modify `.SLDPRT` files in the `共轴手装配体/` folder
2. **Test Assembly**: Validate changes in the main assembly
3. **Update Documentation**: Revise related documents and version info
4. **Export Updates**: Generate new STEP/STL files

**Version Management Best Practices:**
- Preserve original design files
- Create version branches for significant improvements
- Maintain a detailed change log

---

## ⚠️ Important Notes

- Files designed with SolidWorks 2024
- Opening with other SolidWorks versions may require conversion
- Some part dimensions are optimized for 3D printing
- Review the parts list carefully before assembly

---

## 📚 Related Resources

- [SolidWorks Official Documentation](https://www.solidworks.com)
- [STEP File Format Specification](https://en.wikipedia.org/wiki/ISO_10303)
- [3D Printing Best Practices](https://www.prusaprinters.org)

---

## 📞 Contact Information

- **Email**: hurz2024@shanghaitech.edu.cn
- **Authors**: TriCoSphere Design Team
- **Institution**: ShanghaiTech University

---

## 📄 License & Terms of Use

**License**: CC BY-NC-SA 4.0 (Attribution-NonCommercial-ShareAlike 4.0 International)

You are free to:
- **Share** — Copy and redistribute the material in any medium or format
- **Adapt** — Remix, transform, and build upon the material

Under the following terms:
- **Attribution** — You must give appropriate credit, provide a link to the license, and indicate if changes were made
- **NonCommercial** — You may not use the material for commercial purposes
- **ShareAlike** — If you remix, transform, or build upon the material, you must distribute your contributions under the same license as the original

**Details**: https://creativecommons.org/licenses/by-nc-sa/4.0/


**Commercial Licensing:**
If you are a company or institution interested in using the TriCoSphere Hand for commercial purposes, please contact us to negotiate a commercial license:
📧 Email: [hurz2024@shanghaitech.edu.cn]


---

**Thank you for your interest in the TriCoSphere Hand project!** 🙌

For questions or suggestions, please contact us via email.


