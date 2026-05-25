# Fred Fu | Portfolio

一个现代化的个人作品集网站，展示我的项目、博客文章和联系方式。

## 🌟 项目特点

- **响应式设计**：完美适配桌面、平板和移动设备
- **暗色模式**：支持明暗主题切换
- **现代化 UI**：使用 Tailwind CSS 构建的精美界面
- **粒子动画**：优雅的粒子背景效果
- **流畅交互**：平滑滚动和过渡动画

## 📁 项目结构

```
.
├── index.html              # 首页（个人介绍、技能、精选项目）
├── projects.html           # 项目列表页
├── project-detail.html     # 项目详情页模板
├── blog.html               # 博客列表页
├── post.html               # 博客文章页模板
├── contact.html            # 联系页面
├── posts.json              # 博客文章数据
├── projects.json           # 项目数据
├── posts/                  # 博客 Markdown 源文件
│   ├── my-first-vibe.md
│   └── blog-mcm.md
└── projects/               # 项目 Markdown 源文件
    ├── taskflow-ai.md
    ├── minimalist-blog.md
    ├── datalens.md
    ├── light-shadow.md
    ├── quant-models.md
    └── c-practise.md
```

## 🚀 技术栈

- **前端框架**：原生 HTML5 + JavaScript (ES6+)
- **样式库**：Tailwind CSS (CDN)
- **字体**：Inter (Google Fonts)
- **图标**：Font Awesome
- **图表**：Chart.js / D3.js (部分项目)
- **部署**：Vercel / Netlify 兼容

## 📦 项目展示

### Web 应用
- **TaskFlow AI** - 智能任务调度系统 (React + TypeScript + LLM)
- **Minimalist Blog** - 极简博客主题 (Astro + TailwindCSS)

### 数据可视化
- **DataLens** - 实时数据可视化仪表盘 (D3.js + WebSocket)
- **Quant Models Lab** - 量化策略模型实验室 (Python + Pandas)

### 设计作品
- **Light & Shadow** - 摄影作品集网站 (响应式 + 瀑布流布局)

### 实验项目
- **C Code Workshop** - C 语言编程练习合集

## 📝 博客分类

- **技术** - 前端开发、Vibecoding、数学建模
- **量化与投资** - 量化交易策略、回测框架
- **体育** - 足球战术分析
- **余白** - 生活随笔与思考

## 🛠️ 本地运行

1. 克隆仓库
```bash
git clone <repository-url>
cd <project-directory>
```

2. 直接使用浏览器打开 `index.html`，或使用本地服务器：
```bash
# 使用 Python 内置服务器
python -m http.server 8000

# 或使用 Node.js 的 http-server
npx http-server -p 8000
```

3. 访问 `http://localhost:8000`

## 📄 添加新内容

### 添加博客文章
1. 在 `posts/` 目录创建 Markdown 文件
2. 在 `posts.json` 中添加文章元数据

### 添加项目
1. 在 `projects/` 目录创建 Markdown 文件
2. 在 `projects.json` 中添加项目信息

## 🎨 自定义主题

在 `index.html` 的 `<style>` 标签中修改 CSS 变量来调整主题颜色：

```css
:root {
    --bg: #f9f9f9;              /* 背景色 */
    --text-primary: #1a1a1a;    /* 主文字色 */
    --particle-color: rgba(59, 130, 246, 0.12); /* 粒子颜色 */
}
```

## 📱 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 📧 联系方式

通过 [contact.html](contact.html) 页面的表单联系我，或访问我的 GitHub 主页。

## 📜 许可证

MIT License

---

**作者**: Fred Fu  
**最后更新**: 2026 年 5 月
