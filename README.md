
# 个人简历网站（JONAS LI）

[![](https://camo.githubusercontent.com/7a1e6d0c9d4a9b2e0d5b7e4c8d0f5e6a2f4c9e8d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f2545322539382539322545352542382538332545372542362542312d2545352539352538442545352542412541392d427974652545322539382539312532302537432532302542462542432545372538312542332545352538352542382545362539432541432542462542432545372538412542362545342542382541432545352541442541372d626c7565)](https://github.com/)
[![](https://camo.githubusercontent.com/6f5e2b7c3e4a8b1f2e3d4c5b6a7e8f9d0e1c2b3a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d4d49542d79656c6c6f77)](https://opensource.org/licenses/MIT)
[![](https://camo.githubusercontent.com/4f3a2e1d0c9b8a7d6e5f4c3b2a1e0f9d8c7b6a5f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d77656c636f6d652d627269676874677265656e)](http://makeapullrequest.com)

> 响应式、多语言、支持主题切换的个人简历网站，专为求职展示设计。代码完全开源，易于修改和部署。

---

## 主要功能

| 功能 | 说明 |
|------|------|
| ![](https://camo.githubusercontent.com/7c8b9a0e2d4c6f8a1b3e5d7c9a0f2e4d6b8c0a1e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe4b889e8afade58887e68da22de4b8ade69687e68b92e68891e68890e588862d626c7565) | 中文、英文、缅甸语（缅甸语有特殊字体优化） |
| ![](https://camo.githubusercontent.com/5d7e8f9b0c2a4d6e1f3a5c7b9e0d2f4a6b8c0d1e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe4b8bbe9a2982de6b7b1e889b2253230253743254538253830422545352538412541382545392541312542322d707572706c65) | 自动跟随系统或手动切换，配色 Web3 风格 |
| ![](https://camo.githubusercontent.com/2e4f6a8c0d1b3e5f7a9c0e2d4b6f8a1e3c5d7b9f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe58aa8e794bb2de68993e5ad97e69cbae69588e69e9c2d6f72616e6765) | 技能描述和个人总结部分带有逐字打印效果 |
| ![](https://camo.githubusercontent.com/1a3c5e7f9b0d2e4f6a8c1e3f5b7d9e0f2a4c6e8f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe8aebfe997aee7bb9fe8aea12de4b88de7ae97e5ad902532302537432532305741552d627269676874677265656e) | 集成不蒜子统计总访问量，WAU 实时在线人数 |
| ![](https://camo.githubusercontent.com/9b0d2f4a6c8e1a3e5f7b9d0f2e4c6a8b0e2d4f6a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe79599e8a880e69dbf2d4769736375732d707572706c65) | 集成 Giscus，基于 GitHub Discussions 的评论系统 |
| ![](https://camo.githubusercontent.com/3e5f7a9c0d2b4e6f8a1c3e5b7d9f0e2d4c6a8b0f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe7ae80e58e86e4b88be8bdbd2d5044462545322538302541442545342542382538302545392539342541452545342542382538422545352539362541432d6f72616e6765) | 一键下载 PDF 版简历（需自行放置文件） |
| ![](https://camo.githubusercontent.com/2b4d6f8a0c1e3f5b7d9e0f2a4c6e8a1b0d2f4e6a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe5b883e5b1802de5ae8ce585a8e5938de5ba94e5bc8f2d6c6967687467726579) | 手机、平板、电脑自适应布局 |

---

## 支持的语言

| 语言 | 代码 | 说明 |
|------|------|------|
| ![](https://camo.githubusercontent.com/8c9d0e2f4a6b8c0d1e3f5a7b9c0e2d4f6a8c0d1e/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe7ae80e4bd93e4b8ade696872d7a682d626c7565) | `zh` | 默认语言 |
| ![](https://camo.githubusercontent.com/3e5f7a9c0d2b4e6f8a1c3e5b7d9f0e2d4c6a8b0f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f456e676c6973682d656e2d726564) | `en` | 完整英文翻译 |
| ![](https://camo.githubusercontent.com/1a3c5e7f9b0d2e4f6a8c1e3f5b7d9e0f2a4c6e8f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d79616e6d61722d6d792d627269676874677265656e) | `my` | 使用 Noto Serif Myanmar 字体，支持缅甸语换行 |

> 所有文本均通过 `data-zh`、`data-en`、`data-my` 属性存储，前端 JS 动态切换。

---

## 技术栈

| 类别 | 使用技术 |
|------|----------|
| ![](https://camo.githubusercontent.com/2b4d6f8a0c1e3f5b7d9e0f2a4c6e8a1b0d2f4e6a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe59fbae7a1802d48544d4c35253230253743253230435353332532302537432532304a6176615363726970742d6f72616e6765) | HTML5 + CSS3 + 原生 JavaScript (ES6) |
| ![](https://camo.githubusercontent.com/4a6c8e0b2d4f6a8c0d1e3f5b7d9e0f2a4c6e8a1b/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe59bbee6a087e5ba932d466f6e7425417765736f6d65253230362d626c7565) | Font Awesome 6 (免费 CDN) |
| ![](https://camo.githubusercontent.com/6a8c0d1e3f5b7d9e0f2a4c6e8a1b0d2f4e6a8c0d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe5ad97e4bd932d476f6f676c65253230466f6e74732d6c69676874626c7565) | Google Fonts：Orbitron, Space Mono, Noto Sans SC, Noto Serif Myanmar |
| ![](https://camo.githubusercontent.com/1a3c5e7f9b0d2e4f6a8c1e3f5b7d9e0f2a4c6e8f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe8af84e8aebaee7bb9fe79f9f2d4769736375732d707572706c65) | Giscus（需配置 GitHub 仓库） |
| ![](https://camo.githubusercontent.com/9b0d2f4a6c8e1a3e5f7b9d0f2e4c6a8b0e2d4f6a/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe8aebfe997aee7bb9fe8aea12de4b88de7ae97e5ad502532302537432532305741552d627269676874677265656e) | 不蒜子 + WAU（实时在线） |
| ![](https://camo.githubusercontent.com/2e4f6a8c0d1b3e5f7a9c0e2d4b6f8a1e3c5d7b9f/68747470733a2f2f696d672e736869656c64732e696f2f62616467652fe58aa8e794bb2de7baaf4353532d79656c6c6f77) | 纯 CSS（滚动显现、打字机、漂浮光晕） |

---

## 文件结构

```

/
├── index.html          # 主页面（包含所有样式、脚本、内容）
├── JONAS_CV_Update.pdf # PDF 简历文件（需自行放入）
└── README.md           # 项目说明（本文件）

```

> 整个项目就是一个 HTML 文件，所有 CSS/JS 都内嵌，方便复制、修改和部署。

---

## 如何修改内容

### 1. 修改个人信息（头像、姓名、标签等）
在 `index.html` 中找到 `<!-- Hero -->` 区域，修改以下部分：
```html
<div class="hero-name">李恩伟 | JONAS LI</div>
<div class="hero-title" data-zh="..." data-en="..." data-my="...">...</div>
<div class="hero-meta">...</div>
```

· 头像是一个圆形占位符 <div class="avatar-placeholder">李</div>，可以换成自己的图片，或改成 background-image。
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

CSS 顶部有两组颜色变量（[data-theme="dark"] 和 [data-theme="light"]）。可以修改 --accent、--bg 等变量来调整整体色调。

6. 配置 Giscus 留言板

需要替换 data-repo、data-repo-id、data-category、data-category-id 等参数。请访问 Giscus 官网 生成自己的配置。

7. 更新 PDF 简历文件

将您的 PDF 简历命名为 JONAS_CV_Update.pdf 并放在网站根目录，或修改 href 路径。

---

部署方式

· GitHub Pages：直接上传 index.html 和 PDF 文件到仓库，开启 Pages 功能即可。
· Netlify / Vercel / Cloudflare Pages：拖拽上传即可。

---

注意事项

· 缅甸语文本使用了 Noto Serif Myanmar 字体，需确保加载正常。
· 访问统计中的 WAU 服务可能在某些网络环境下较慢，不影响主要功能。
· 如果您不需要 Giscus 评论功能，可以删除对应的 section 和脚本。

---

开源协议

MIT License
本项目为开源模板，您可随意修改和使用，无需保留原作者署名（但欢迎保留链接）。

---

Made with ❤️ for job seekers