# 温新宇 Miles · 个人作品集

求职用单页作品集，面向 AI PM（文艺写作方向）。

- **技术栈**：纯 HTML / CSS / JS 单文件（`index.html`），无框架依赖
- **部署**：Vercel 静态托管
- **视觉**：Notion 风格，极简克制

## 本地预览

```bash
python3 -m http.server 8090
# 打开 http://localhost:8090
```

## 目录结构

```
/
├── index.html                # 整站单文件（HTML + CSS + JS 全部内联）
├── vercel.json               # Vercel 静态部署配置
├── .gitignore
└── assets/
    ├── screenshots/          # 项目截图
    ├── videos/               # 视频（已压缩版本 ttnet-web.mp4）
    ├── readmes/              # 每个项目的 README（Markdown）
    ├── moment-demo.html      # 片刻项目的在线 demo
    ├── ganjiangmoye-script.pdf
    └── gangjiangmoye-rank.JPG
```

## 修改内容

- **项目 / 写作数据**：直接改 `index.html` 里的 `projects` / `writings` 数组
- **项目 README**：改 `assets/readmes/<项目id>.md`，浏览器刷新即更新
- **截图 / 视频**：替换 `assets/screenshots/` / `assets/videos/` 下同名文件
