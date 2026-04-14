# ADA 2026 糖尿病诊疗指南 · 中文科普网站

基于美国糖尿病协会（ADA）2026年版《糖尿病诊疗标准》(*Diabetes Care* 2026;49(Suppl 1):S1–S320) 的权威中文科普解读网站。

## 项目简介

本网站系统解读 ADA 2026 指南核心内容，涵盖糖尿病的预防、诊断、治疗与管理，以现代化、响应式的中文科普页面呈现，面向大众与医疗从业者。

> **免责声明：** 本网站内容基于循证医学整理，仅供健康科普和教育目的，不构成个人医疗建议、诊断或治疗方案。请就个人健康问题咨询专业医疗人员。

## 页面结构

| 页面 | 文件 | 内容 |
|------|------|------|
| 首页 | `index.html` | 项目总览、指南背景、导航入口 |
| 概述与诊断 | `overview.html` | 糖尿病分型、诊断标准、T1D分期筛查、CGM核心指标 |
| 预防 | `prevention.html` | 生活方式干预、药物预防、电子烟更新、PI3Kα/激素预防 |
| 综合管理 | `treatment.html` | 饮食/运动/药物三优先算法、5类药物详解、T1D药物、CGM/AID/血糖监测 |
| 心肾保护 | `heart-kidney.html` | 肥胖评估与减重、血压血脂、抗血小板、心衰、CKD四重疗法、转诊指征 |
| 并发症 | `complications.html` | DKA/HHS、低血糖分级、视网膜/神经/足部病变、老年/妊娠/儿童/住院/抗癌治疗 |
| 身心健康 | `wellbeing.html` | 糖尿病困扰筛查、DSMES、AID/连接笔、数字健康、5大范式转变、管理清单、参考文献 |

## 技术栈

- **HTML5** — 语义化页面结构
- **Tailwind CSS** (CDN) — 原子化样式框架
- **Noto Serif SC / Noto Sans SC** — 中文字体（Google Fonts）
- **原生 JavaScript** — 滚动动画、交互逻辑

无构建步骤，纯静态页面，直接打开 `index.html` 即可浏览。

## 本地运行

```bash
# 方式一：直接打开
open index.html          # macOS
start index.html         # Windows

# 方式二：本地服务器（推荐，避免字体跨域问题）
npx serve .
# 或
python -m http.server 8000
```

## 设计特色

- **响应式设计** — 适配手机、平板、桌面端
- **Sage + Coral 配色** — 沉稳绿调搭配警示橙，兼顾专业感与可读性
- **滚动淡入动画** — `fade-up` 渐现效果，尊重 `prefers-reduced-motion`
- **卡片悬停交互** — `card-hover` 微动效提升浏览体验
- **2026 更新标记** — 指南新增/修订内容以 `2026 更新` 标签醒目标注

## 科普视频

- 📺 [ADA 2026 糖尿病诊疗指南 · 中文科普解读（B站）](https://www.bilibili.com/video/BV14sQgBqEg9/?share_source=copy_web&vd_source=e712953f066cd56c2ad96e8d1a7376a0)
- 📺 [ADA 2026 糖尿病诊疗指南 · 科普视频解读（YouTube）](https://www.youtube.com/watch?v=IfsqEXqUnUQ)

[![ADA 2026 糖尿病诊疗指南 · 科普视频解读](https://img.youtube.com/vi/IfsqEXqUnUQ/maxresdefault.jpg)](https://www.youtube.com/watch?v=IfsqEXqUnUQ)

## 内容来源

- American Diabetes Association Professional Practice Committee for Diabetes. *Standards of Care in Diabetes—2026*. Diabetes Care. 2026;49(Suppl 1):S1–S320.
- American Diabetes Association Professional Practice Committee for Diabetes. *Summary of Revisions: Standards of Care in Diabetes—2026*. Diabetes Care. 2026;49(Suppl 1):S6–S12.
- International Diabetes Federation. *IDF Diabetes Atlas*. 10th ed. 2021.

## 项目文件

```
├── index.html              # 首页
├── overview.html           # 概述与诊断
├── prevention.html         # 预防策略
├── treatment.html          # 综合管理
├── heart-kidney.html       # 心肾保护
├── complications.html      # 并发症管理
├── wellbeing.html          # 身心健康与参考文献
├── ada2026_diabetes_guide.md  # 原始科普文档
└── README.md               # 本文件
```

## License

本科普网站内容仅供教育参考，原始指南版权归 American Diabetes Association 所有。
