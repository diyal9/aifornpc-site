---
version: alpha
name: Lingjing V4 (AI NPC Infrastructure)
description: Engineering Precision meets Narrative Depth. Removes generic "AI hype" (neon, blobs, glass) in favor of structural elegance, high-contrast typography, and subtle technical aesthetics.
colors:
  primary: "#0B1120"     # Deep Space Blue (Background)
  secondary: "#1E293B"   # Slate 800 (Cards/Surfaces)
  accent: "#D4AF37"      # Champagne Gold / Metallic (Interaction & Status - replacing neon cyan)
  neutral: "#F8FAFC"     # Crisp White (Text & Headings)
  subtle: "#334155"      # Muted Slate (Borders, Grid lines)
typography:
  h1:
    fontFamily: "Noto Serif SC, serif"
    fontSize: "4rem"
    fontWeight: 700
    lineHeight: 1.1
    letterSpacing: "-0.03em"
  h2:
    fontFamily: "Inter, sans-serif"
    fontSize: "2.25rem"
    fontWeight: 600
    lineHeight: 1.2
    letterSpacing: "-0.02em"
  body-md:
    fontFamily: "Inter, sans-serif"
    fontSize: "1rem"
    fontWeight: 400
    lineHeight: 1.6
rounded:
  sm: 2px
  md: 4px
  lg: 12px
spacing:
  sm: 16px
  md: 32px
  lg: 64px
  xl: 128px
components:
  hero-title:
    typography: "{typography.h1}"
    textColor: "{colors.neutral}"
  section-title:
    typography: "{typography.h2}"
    textColor: "{colors.neutral}"
  card-bg:
    backgroundColor: "{colors.secondary}"
    rounded: "{rounded.lg}"
    padding: 32px
    border: "1px solid {colors.subtle}"
  button-primary:
    backgroundColor: "{colors.accent}"
    textColor: "{colors.primary}"
    rounded: "{rounded.md}"
    padding: "12px 24px"
---

## 品牌美学原则 (去 AI 味)

1.  **拒绝光污染**: 移除所有大面积径向渐变、霓虹青/紫色、悬浮粒子。
2.  **秩序感**: 使用 1px 的网格线和边框来构建结构，强调工程属性而非魔幻属性。
3.  **字体层级**: 大标题使用 **Noto Serif SC** (人文感/权威感)，正文使用 **Inter** (现代感/易读性)。
4.  **色彩策略**: 深色背景 (#0B1120) 搭配 暖金/香槟色 (#D4AF37) 点缀，替代冷色科技光。
5.  **产品展示**: 使用线框图 (Wireframes) 或 代码片段 (Code Snippets) 作为配图，展示真实能力，而非抽象的 3D 插图。

## Components

*   **卡片**: 纯深色背景 + 细边框，悬停时边框变色，无阴影扩散。
*   **按钮**: 实体色块，无渐变，圆角小 (4px)。
*   **代码区**: JetBrains Mono，暗色背景，高亮语法。
