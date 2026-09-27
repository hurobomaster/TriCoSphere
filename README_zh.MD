# TriCoSphere 机械手

TriCoSphere Hand 是当前 Trico-hand 平台的前代模块化并联机械手。本仓库发布中立格式的几何文件，用于科研、查看和加工。

## 项目信息

- 版本：1.0
- 项目周期：2025 年 3 月至 2025 年 9 月
- 发表会议：ICRA 2026
- 许可证：CC BY-NC-SA 4.0

## 发布文件

```text
TriCoSphere/
├── STEP/
│   └── TriCoSphere.STEP     # 中立 CAD 格式的完整装配体
└── STL/                     # 用于加工的单独网格文件
```

本仓库仅分发 STEP 和 STL 几何文件，不包含原生可编辑 CAD 源文件。

## 文件格式

| 格式 | 用途 | 常用软件 |
|---|---|---|
| STEP | 跨平台查看完整装配体和交换几何数据 | FreeCAD、Fusion 360 及其他支持 STEP 的 CAD 软件 |
| STL | 网格查看、切片和 3D 打印 | Cura、PrusaSlicer 及其他网格工具 |

## 使用方法

### 完整装配体

使用支持 STEP 的 CAD 软件打开 `STEP/TriCoSphere.STEP`，查看完整装配体几何。

### 单独零件

使用 `STL/` 目录中的文件进行网格查看和加工。制造前请确认单位、比例、公差和打印方向。

## 联系方式

- 邮箱：hurz2024@shanghaitech.edu.cn
- 作者：TriCoSphere Design Team
- 机构：上海科技大学

## 许可证

发布内容采用 CC BY-NC-SA 4.0 许可证。详情见 [LICENSE](LICENSE) 和[许可证条款](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)。

如需商业许可，请通过邮箱联系项目团队。
