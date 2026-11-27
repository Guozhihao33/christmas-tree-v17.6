# Christmas Tree · v17.6

一棵会呼吸的星空圣诞树 —— 纯前端单文件实现，无需任何依赖，打开即看。

## 在线预览

GitHub Pages：`https://<username>.github.io/christmas-tree-v17.6/`

## 特点

- **纯 Canvas 2D 实时渲染**：手写透视投影 + 深度衰减，无 Three.js、无外部 CDN，离线也能跑
- **6800+ 针叶粒子**：分层冷杉轮廓，由内向外的体积感
- **460 颗螺旋灯带**：冷暖双色，逐颗呼吸闪烁
- **78 颗挂饰球**：金、红、冰蓝、白四色高光
- **树顶星**：六道旋转光芒 + 呼吸光晕
- **三层景深飘雪**：近景柔焦、远景细雪
- **交互**：拖动旋转（带惯性）、滚轮缩放、静止 0.9 秒后自动慢转
- **自适应**：DPR 高清渲染，手机端同样适配

## 使用

```bash
# 直接打开
open index.html        # macOS
xdg-open index.html    # Linux
```

或把 `index.html` 丢到任意静态托管（GitHub Pages / Vercel / 对象存储）即可。

## 结构

```
christmas-tree-v17.6/
├── index.html    # 全部内容（HTML + CSS + JS）
└── README.md
```

## 调参

在 `index.html` 的 `CFG` 对象里可以快速调整：

| 参数 | 含义 | 默认 |
| --- | --- | --- |
| `treeH` / `treeR` | 树高 / 底部半径 | 7.4 / 2.62 |
| `camDist` | 相机距离（缩放） | 12.2 |
| `spin` | 自动旋转速度 | 0.00055 |
| `yaw` | 初始角度 | 0.62 |

---

Merry Christmas · 2026
