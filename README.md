# vovo 的知识花园

> 个人数字花园 — 读书、写作、视频笔记的长期沉淀地。
> 在线访问：https://iamvovo2049.github.io/vovo2039/

## 技术栈

- **静态站点**：Quartz v4
- **写作**：Obsidian（本地编辑）
- **托管**：GitHub Pages
- **AI 整理**：OpenRouter（Claude / Gemini）
- **视频转录**：本机 TubeScribe（独立项目）

## 本地开发

```bash
npm install                  # 安装依赖
npx quartz build --serve     # 本地预览（默认 :8080）
npx quartz build             # 仅构建到 ./public
```

## 内容结构

```
content/
├── 00-花园说明/        说明页 / 关于本站
├── 10-MOC/             主题地图（Maps of Content）
├── 20-读书/            读书笔记 / 书摘
├── 30-写作/            原创内容（🌱种子 / 🌿萌芽 / 🌳成长）
├── 40-视频笔记/        YouTube 转录 + 精读
├── 50-卡片/            Zettelkasten 原子卡片
└── 99-meta/            模板与配置
```

## 部署

push 到 `main` 分支时，GitHub Action 自动构建并部署到 GitHub Pages。

详见 `.github/workflows/deploy.yml`。

## 灵感来源

- [Andy Matuschak's notes](https://notes.andymatuschak.org/)
- [Maggie Appleton](https://maggieappleton.com/)
- [brave2049](https://brave2049.com/)

## License

内容版权归 vovo 所有。代码部分继承 Quartz v4 (MIT)。
