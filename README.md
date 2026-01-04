# Web3 空投资讯博客

一个专注于分享 Web3 空投信息和项目资讯的个人博客，使用纯 HTML、CSS 和 JavaScript 构建，可直接部署到 GitHub Pages。

## 🚀 功能特点

- ✅ 响应式设计，支持移动端和桌面端
- ✅ 现代化的深色主题 UI
- ✅ 文章分类和标签系统
- ✅ 平滑滚动和动画效果
- ✅ 无需构建工具，开箱即用
- ✅ SEO 友好的元数据

## 📁 项目结构

```
web3-airdrop-blog/
├── index.html              # 首页
├── articles.html           # 文章列表页
├── about.html              # 关于页面
├── article-layerzero.html  # LayerZero 文章
├── article-zksync.html     # zkSync 文章
├── article-starknet.html   # Starknet 文章
├── article-base.html       # Base 文章
├── article-arbitrum.html   # Arbitrum 文章
├── article-optimism.html   # Optimism 文章
├── styles.css              # 样式文件
├── script.js               # JavaScript 文件
└── README.md               # 项目说明
```

## 🎨 技术栈

- **HTML5** - 语义化标签
- **CSS3** - Flexbox、Grid、动画
- **JavaScript** - 交互功能
- **GitHub Pages** - 静态网站托管

## 📦 部署到 GitHub Pages

### 方法一：通过 GitHub 网页界面部署

1. **创建 GitHub 仓库**
   - 访问 https://github.com/new
   - 创建一个新仓库（例如：`web3-airdrop-blog`）
   - 选择 Public 或 Private（Public 可以免费使用 GitHub Pages）

2. **上传文件**
   - 将项目中的所有文件上传到仓库
   - 可以拖拽上传或使用 "Upload files" 按钮

3. **启用 GitHub Pages**
   - 进入仓库的 Settings 页面
   - 在左侧菜单中找到 "Pages"
   - 在 "Build and deployment" 下，选择 "Source" 为 "Deploy from a branch"
   - 选择 "Branch" 为 "main" 或 "master"
   - 点击 "Save"

4. **等待部署**
   - GitHub 会自动部署你的网站
   - 几分钟后，你会在 Pages 页面看到你的网站 URL
   - 格式通常是：`https://你的用户名.github.io/仓库名/`

### 方法二：通过 Git 命令行部署

```bash
# 1. 初始化 Git 仓库
cd web3-airdrop-blog
git init

# 2. 添加所有文件
git add .

# 3. 提交更改
git commit -m "Initial commit: Web3 空投资讯博客"

# 4. 添加远程仓库（替换为你的仓库地址）
git remote add origin https://github.com/你的用户名/web3-airdrop-blog.git

# 5. 推送到 GitHub
git branch -M main
git push -u origin main

# 6. 按照"方法一"中的步骤 3 启用 GitHub Pages
```

## 📝 自定义内容

### 修改网站信息

编辑 `index.html` 和 `articles.html` 中的以下内容：

```html
<!-- 网站标题 -->
<title>你的标题</title>

<!-- 导航栏 -->
<div class="nav-brand">
    <h1>你的网站名称</h1>
</div>

<!-- 页脚 -->
<footer class="footer">
    <p>&copy; 2026 你的名字. 保留所有权利.</p>
</footer>
```

### 添加新文章

1. 复制现有的文章模板（如 `article-layerzero.html`）
2. 重命名为 `article-新文章.html`
3. 修改文章内容、标题、日期和标签
4. 在 `index.html` 和 `articles.html` 中添加文章链接

### 修改样式

编辑 `styles.css` 文件，自定义颜色、字体和布局：

```css
:root {
    --primary-color: #6366f1;    /* 主色调 */
    --secondary-color: #8b5cf6;  /* 次要色调 */
    --accent-color: #ec4899;     /* 强调色 */
    --dark-bg: #0f172a;          /* 深色背景 */
    --light-bg: #1e293b;         /* 浅色背景 */
}
```

## 🎯 使用建议

1. **定期更新内容**：保持文章的时效性，及时更新空投信息
2. **添加免责声明**：在每篇文章中添加投资风险提示
3. **优化 SEO**：为每篇文章添加合适的标题、描述和关键词
4. **响应式测试**：在不同设备上测试网站显示效果
5. **性能优化**：压缩图片、优化 CSS 和 JavaScript

## 🔧 本地预览

你可以使用本地服务器预览网站：

### 使用 Python

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

### 使用 Node.js

```bash
# 安装 http-server
npm install -g http-server

# 启动服务器
http-server -p 8000
```

然后在浏览器中访问 `http://localhost:8000`

## 📊 自定义域名（可选）

如果你有自己的域名，可以配置自定义域名：

1. 在 GitHub 仓库的 Settings > Pages 中添加自定义域名
2. 在你的域名提供商处添加 CNAME 记录，指向 `你的用户名.github.io`
3. 等待 DNS 生效（通常需要几分钟到几小时）

## 🤝 贡献

欢迎提交 Issue 和 Pull Request 来改进这个项目！

## ⚠️ 免责声明

本博客内容仅供参考，不构成投资建议。Web3 空投具有高风险，请读者自行研究和评估项目风险，仅投入可承受损失的资金。

## 📄 许可证

MIT License

## 🌟 致谢

感谢所有为 Web3 生态系统做出贡献的开发者和社区成员！

---

**开始使用**：按照上述步骤部署到 GitHub Pages，几分钟内即可拥有自己的 Web3 空投博客！