# TriCoSphere Hand

TriCoSphere Hand is a modular parallel robotic hand developed as the predecessor to the current Trico-hand platform. This repository publishes neutral-format geometry for research, visualization, and fabrication.

## Project information

- Version: 1.0
- Project period: March 2025–September 2025
- Conference: ICRA 2026
- License: CC BY-NC-SA 4.0

## Released files

```text
TriCoSphere/
├── STEP/
│   └── TriCoSphere.STEP     # Complete assembly in neutral CAD format
└── STL/                     # Individual mesh exports for fabrication
```

Only STEP and STL geometry is distributed. Native editable CAD source files are not included.

## File formats

| Format | Purpose | Typical software |
|---|---|---|
| STEP | Cross-platform assembly inspection and geometry exchange | FreeCAD, Fusion 360, and other STEP-compatible CAD tools |
| STL | Mesh inspection, slicing, and 3D printing | Cura, PrusaSlicer, and other mesh tools |

## Usage

### Complete assembly

Open `STEP/TriCoSphere.STEP` in a STEP-compatible CAD application to inspect the complete assembly geometry.

### Individual parts

Use the files under `STL/` for mesh inspection and fabrication workflows. Confirm units, scale, tolerances, and print orientation before manufacturing.

## Contact

- Email: hurz2024@shanghaitech.edu.cn
- Authors: TriCoSphere Design Team
- Institution: ShanghaiTech University

## License

The released material is licensed under the CC BY-NC-SA 4.0 license. See [LICENSE](LICENSE) and the [license terms](https://creativecommons.org/licenses/by-nc-sa/4.0/) for details.

For commercial licensing, contact the project team by email.
