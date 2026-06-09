# 终焉与始源

> 少年成长 × 浪漫冒险 × 政治斗争 — 在终结与新生之间，选择守护而非毁灭。

## 在线阅读

👉 **[终焉与始源 - GitHub Pages](https://una539.github.io/novels/)**

## 项目结构

```
novels/
├── docs/               # GitHub Pages 网站（docsify）
│   ├── index.html      # 入口
│   ├── README.md       # 首页
│   ├── _coverpage.md   # 封面
│   ├── _sidebar.md     # 侧边导航
│   ├── chapter-*.md    # 各章正文
│   ├── outline.md      # 故事大纲
│   ├── characters.md   # 角色设定
│   ├── world-building.md  # 世界观
│   ├── _glossary.md    # 术语表
│   ├── style-guide.md  # 写作风格指南
│   └── _tracker.md     # 写作追踪
├── chapter-*.md        # 正文源文件
├── outline.md
├── characters.md
├── world-building.md
├── _glossary.md
├── style-guide.md
├── _tracker.md
└── README.md
```

## 本地预览

```bash
# 安装 docsify-cli
npm i -g docsify-cli

# 启动本地服务
docsify serve docs
```

## 部署状态

GitHub Pages 通过 `main` 分支的 `/docs` 目录自动部署。
