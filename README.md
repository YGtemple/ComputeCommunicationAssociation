# 校园AI&计算机交流社群 · 新手指南

> 一个面向校园 AI 与计算机爱好者的交流社群官方新手指南页面，帮助新人快速了解社群、融入集体、获取资源。

![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

## 📖 项目简介

本项目是「校园AI&计算机交流社群」的官方新手指南单页网站，采用纯 HTML + CSS + JavaScript 实现，无需后端依赖，可直接部署到任意静态托管平台。

页面以现代化的视觉设计，系统地介绍了社群定位、入群流程、成员福利、团队构成、合作资源、活动安排以及社群规范，是新人入群后的第一站。

## ✨ 功能亮点

- **社群介绍** — 清晰阐述社群定位与核心价值
- **入群三步走** — 改备注 → 看公告 → 自我介绍，引导新人快速融入
- **成员福利展示** — 学习资料、答疑互助、赛事组队、算力与内推四大板块
- **团队成员介绍** — 展示核心团队成员的能力方向、个人优势、项目经历
- **合作资源专区** — 字节跳动·火山引擎算力扶持、技术赋能、实习通道
- **活动日历** — 技术交流、赛事组队、线下沙龙、简历内推、项目探讨
- **社群规范** — 明确群规与氛围建设要求
- **响应式设计** — 适配桌面端与移动端浏览

## 🛠 技术栈

| 类别 | 技术 |
|------|------|
| 标记语言 | HTML5 |
| 样式 | CSS3（CSS 变量、Grid、Flexbox、渐变、动画） |
| 交互 | 原生 JavaScript |
| 图标 | 内联 SVG / Emoji |
| 部署 | 任意静态托管（GitHub Pages / Netlify / Vercel） |

## 📁 项目结构

```
ComputeCommunicationAssociation/
├── index.html          # 主页面（包含全部内容与样式）
├── qq_qrcode.jpg       # QQ 群二维码图片
└── README.md           # 项目说明文档
```

## 🚀 快速开始

### 本地预览

直接用浏览器打开 `index.html` 即可：

```bash
# 方式一：双击打开
open index.html

# 方式二：使用本地服务器（推荐）
python3 -m http.server 8080
# 然后访问 http://localhost:8080
```

### 部署上线

本项目为纯静态页面，可部署到任意静态托管平台：

**GitHub Pages：**
```bash
git init
git add .
git commit -m "init: 社群新手指南"
git branch -M main
git remote add origin https://github.com/YGtemple/ComputeCommunicationAssociation.git
git push -u origin main
# 在 GitHub 仓库 Settings → Pages 中启用 GitHub Pages
```

**Netlify / Vercel：** 直接拖拽文件夹或关联仓库即可自动部署。

## 🎨 设计规范

- **主色调**：`#4a6cf7`（科技蓝）、`#7c3aed`（紫色）、`#10b981`（成功绿）
- **背景色**：`#f5f7fa`（浅灰蓝）
- **卡片圆角**：16px
- **字体**：系统字体栈（PingFang SC / Microsoft YaHei / Segoe UI）
- **封面渐变**：`#1a1a2e → #16213e → #0f3460` 深色科技渐变

## 📝 内容板块

1. **封面区域** — 社群名称、Slogan、徽章
2. **信息栏** — 社群类型、成立时间、成员规模等关键信息
3. **QQ 群号横幅** — 入群方式与群号
4. **社群介绍** — 我们做什么
5. **新手指南** — 入群三步走
6. **成员福利** — 四大福利板块详解
7. **参与指南** — 如何更好地参与社群活动
8. **常见问题** — FAQ 答疑
9. **团队介绍** — 核心成员卡片
10. **合作资源** — 字节跳动火山引擎合作专区
11. **活动展示** — 社群活动类型
12. **群规与氛围** — 社群规范
13. **加入我们** — 行动号召

## 🤝 社群介绍

「校园AI&计算机交流社群」是一个面向在校大学生的技术交流社区，聚焦人工智能、计算机科学、算法竞赛、全栈开发等方向。社群致力于为成员提供学习资料共享、技术答疑互助、竞赛组队备赛、算力资源扶持、实习内推通道等全方位支持。

## 📄 许可证

本项目仅供社群内部使用与展示。

## 📮 联系方式

- GitHub：[@YGtemple](https://github.com/YGtemple)
- 社群入口：详见页面内 QQ 群号
