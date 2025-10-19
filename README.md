# 🌌 星日的 Hexo 博客源码

这是我的 Hexo 博客源码仓库，包含所有文章、配置和主题，致力于构建一个 **结构清晰、自动化部署、可复现** 的技术写作平台。

👉 **部署地址**：[https://gengxr.github.io](https://brucegeng66.github.io)

---

## 🧪 本地开发

你可以在本地快速预览和调试博客内容：

```bash
# 安装依赖
npm install

# 启动本地服务器（默认 http://localhost:4000）
hexo server

# 如需清理缓存并重新生成页面
hexo clean
hexo generate

```



---

## 📦 项目结构说明

```text
.
├── _config.yml       # Hexo 主配置文件，控制站点行为与主题设置
├── package.json      # 项目依赖与脚本定义，包含 Hexo 插件与命令
├── scaffolds/        # 文章模板，定义新建文章的默认结构
├── source/           # 博客内容目录（文章、页面、资源）
│   ├── _posts/       # Markdown 格式的博客文章
│   └── images/       # 图片资源，可在文章中引用
├── themes/           # Hexo 主题目录（如 butterfly、next 等）
├── public/           # Hexo 生成的静态页面（自动生成，勿手动修改）
├── .gitignore        # Git 忽略文件配置，避免提交缓存与临时文件
└── README.md         # 当前说明文档，介绍项目结构与使用方式

```

