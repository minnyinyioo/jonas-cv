📄 项目说明：个人简历网站（JONAS LI）

这是一个响应式、多语言、支持主题切换的个人简历网站，专为求职展示设计。代码完全开源，易于修改和部署。

✨ 主要功能

功能 说明
🌍 三语切换 中文、英文、缅甸语（缅甸语有特殊字体优化）
🌗 深色/浅色主题 自动跟随系统或手动切换，配色 Web3 风格
⌨️ 打字机动画 技能描述和个人总结部分带有逐字打印效果
📊 访问统计 集成不蒜子（busuanzi）统计总访问量，WAU 实时在线人数
💬 留言板 集成 Giscus，基于 GitHub Discussions 的评论系统
📄 PDF 简历下载 一键下载 PDF 版简历（需自行放置文件）
📱 完全响应式 手机、平板、电脑自适应布局

🌐 支持的语言

语言 代码 说明
简体中文 zh 默认语言
English en 完整英文翻译
မြန်မာ (缅甸语) my 使用 Noto Serif Myanmar 字体，支持缅甸语换行

所有文本均通过 data-zh、data-en、data-my 属性存储，前端 JS 动态切换。

🛠️ 技术栈

类别 使用技术
基础 HTML5 + CSS3 + 原生 JavaScript (ES6)
图标库 Font Awesome 6 (免费 CDN)
字体 Google Fonts：Orbitron, Space Mono, Noto Sans SC, Noto Serif Myanmar
评论系统 Giscus（需配置 GitHub 仓库）
访问统计 不蒜子 + WAU（实时在线）
动画 纯 CSS（滚动显现、打字机、漂浮光晕）

📂 文件结构

```
/
├── index.html          # 主页面（包含所有样式、脚本、内容）
├── JONAS_CV_Update.pdf # PDF 简历文件（需自行放入）
└── README.md           # 项目说明（本文件）
```

整个项目就是一个 HTML 文件，所有 CSS/JS 都内嵌，方便复制、修改和部署。

✏️ 如何修改内容

1. 修改个人信息（头像、姓名、标签等）

在 index.html 中找到 <!-- Hero --> 区域，修改以下部分：

```html
<div class="hero-name">李恩伟 | JONAS LI</div>
<div class="hero-title" data-zh="..." data-en="..." data-my="...">...</div>
<div class="hero-meta">...</div>
```

· 头像是一个圆形占位符（<div class="avatar-placeholder">李</div>），您可以换成自己的图片，或改成 background-image。
· 每个 meta-chip 包含一个图标和三种语言的文字。

2. 修改技能列表

在 <!-- Skills --> 区域，每个 .skill-card 对应一项技能。修改：

```html
<h3 data-zh="..." data-en="..." data-my="...">危机攻坚与问题解决</h3>
<p class="type-text" data-zh="..." data-en="..." data-my="...">描述文字...</p>
```

· 图标使用 <i class="fas fa-bell"></i>，可参考 Font Awesome 图标库 更换。

3. 修改工作经历

在 <!-- Experience --> 区域，每个 .exp-item 是一个工作经历。修改公司名、职位、职责列表。

4. 修改联系方式和邮箱

在 <!-- Contact --> 区域，修改电话、LINE ID、邮箱地址等。

```html
<a href="mailto:jonas@jtalk.eu.cc" class="contact-card">...</a>
```

5. 更换主题配色

CSS 顶部有两组颜色变量（[data-theme="dark"] 和 [data-theme="light"]）。您可以修改 --accent、--bg 等变量来调整整体色调。

6. 配置 Giscus 留言板

需要替换 data-repo、data-repo-id、data-category、data-category-id 等参数。请访问 Giscus 官网 生成自己的配置。

7. 更新 PDF 简历文件

将您的 PDF 简历命名为 JONAS_CV_Update.pdf 并放在网站根目录，或修改 href 路径。

🚀 部署方式

· GitHub Pages：直接上传 index.html 和 PDF 文件到仓库，开启 Pages 功能即可。
· 任何静态托管：Netlify、Vercel、Cloudflare Pages 等，拖拽上传即可。

📝 注意事项

· 缅甸语文本使用了 Noto Serif Myanmar 字体，需确保加载正常。
· 访问统计中的 WAU 服务可能在国内访问较慢，不影响主要功能。
· 如果您不需要 Giscus 评论功能，可以删除对应的 section 和脚本。

🤝 开源协议

本项目为开源模板，您可随意修改和使用，无需保留原作者署名（但欢迎保留链接）。

---

Made with ❤️ for job seekers
如有问题，欢迎提 Issue 或直接修改代码。