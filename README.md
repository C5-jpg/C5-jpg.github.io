<div align="center">

# 🌐 C5's Blog — 个人技术博客

**Jekyll · GitHub Pages · 响应式设计 · 中文排版优化**

[![Jekyll](https://img.shields.io/badge/Jekyll-4.x-CC0000.svg)](https://jekyllrb.com/)
[![GitHub Pages](https://img.shields.io/badge/Deploy-GitHub%20Pages-222222.svg)](https://pages.github.com/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()

**🎨 PaperMod / Lil'Log 风格 · 磨砂玻璃导航 · 三栏布局 · Noto Serif 中文衬线**

**👉 访问: [c5-jpg.github.io](https://c5-jpg.github.io)**

</div>

---

## 📋 博客特色

### 🎨 设计风格

| 特性 | 实现 |
|:---:|------|
| **排版** | Noto Serif SC 标题 + Noto Sans SC 正文 + JetBrains Mono 代码 |
| **导航** | 磨砂玻璃效果 (backdrop-filter) sticky 头部 |
| **布局** | 800px 最大宽度内容区，响应式断点 (768px / 480px) |
| **功能** | 文章列表 · 分类标签 · 归档页 · RSS 订阅 · SEO 优化 |
| **字体** | Google Fonts 异步加载，中文排版优化 |

### 📄 页面结构

```
┌─────────────────────────────────────────┐
│  🏠 Home   📋 About   📦 Archive       │  ← Sticky 磨砂导航
├─────────────────────────────────────────┤
│                                          │
│  2026-05-22  当 DeepMind 招聘一位哲学家  │
│              AI 时代哲学思维工程化分析    │
│                                          │
│  2026-05-20  ...更多文章...              │
│                                          │
└─────────────────────────────────────────┘
```

---

## 📁 项目结构

```
C5-jpg.github.io/
│
├── 📝 文章
│   └── _posts/
│       └── 2026-05-22-deepmind-philosopher.md    # DeepMind 哲学家分析
│
├── 🎨 布局与样式
│   ├── _layouts/
│   │   ├── default.html    # 基础布局 (头部, 导航, SEO)
│   │   ├── home.html       # 首页 (文章列表)
│   │   └── post.html       # 文章页 (标题, 日期, 标签)
│   └── assets/css/
│       └── style.css       # 490 行自定义样式
│
├── 📄 页面
│   ├── index.html          # 首页
│   ├── about.md            # 关于页
│   └── archive.html        # 归档页
│
├── ⚙️ 配置
│   ├── _config.yml         # Jekyll 配置
│   └── Gemfile             # 依赖 (github-pages gem)
│
└── 📂 其他
    └── _site/              # 构建输出 (gitignored)
```

---

## 🚀 本地运行

```bash
# 安装依赖
bundle install

# 本地开发服务器
bundle exec jekyll serve
# 访问 http://localhost:4000

# 构建静态站点
bundle exec jekyll build
```

---

## 🛠️ 技术栈

| 类别 | 技术 |
|:---:|:---:|
| 静态站点 | Jekyll 4.x |
| 部署 | GitHub Pages (自动) |
| 排版 | Kramdown (GFM) |
| 字体 | Noto Serif SC / Noto Sans SC / JetBrains Mono |
| 样式 | 纯 CSS (CSS Variables) |
| 插件 | jekyll-feed · jekyll-seo-tag |

---

<div align="center">

**⭐ 喜欢这个博客设计？给个 Star！**

</div>
