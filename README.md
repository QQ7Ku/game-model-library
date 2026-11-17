# Game Model Library · 游戏模型库

面向 AI/Agent 与游戏开发的通用 3D 模型集合：**115 个 GLB 模型**，分两个风格包，已按 类别 → 子类 归档。

- [AI_CATALOG.md](AI_CATALOG.md) —— 每个模型的作用、适用场景与路径（AI 优先读这个）
- [catalog.json](catalog.json) —— 机器可读目录（检索/RAG 用）

## 风格包

| 包 | 数量 | 说明 |
|---|---|---|
| `models/acnh_style/` | 60 | 粉彩圆润玩具感，岛屿生活场景（6 类别 / 26 子类） |
| `models/urban_style/` | 55 | 都市动漫·复古 × 潮流，高对比霓虹（8 类别 / 26 子类） |

## 目录结构

```text
models/
  acnh_style/
    01_buildings/ 02_characters/ 03_nature/ 04_furniture/ 05_props/ 06_terrain/
      <subcategory>/models_text/<id>.glb
  urban_style/
    U1_characters/ U2_props/ U3_buildings/ U4_terrain/ U5–U8_variants_*/
      <subcategory>/models_text/<id>.glb
```

## 快速使用

```python
import json, pathlib
catalog = json.loads(pathlib.Path("catalog.json").read_text())
# 按用途找模型
hits = [m for m in catalog["models"] if "商店" in " ".join(m["use_cases"])]
glb = pathlib.Path(hits[0]["model"])  # 直接加载这个 GLB
```

Web（Three.js / model-viewer）直接引用相对路径即可；模型为静态 GLB、无动画，加载后建议按 `target_height` 或包围盒归一化。

## 说明

- 模型由 Lux3D 文生 3D 生成，均为原创设计，仅参考风格语言，不含任何现有游戏的角色/Logo/标识。
- 本仓库只含模型与目录文件；配套游戏界面（Atlas UI）、生成工具与完整项目文档见原工作区。
