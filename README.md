# 龙天彪 - 物联网安全工程师个人主页

一个现代化、响应式的个人主页，展示物联网安全专业能力、项目经历和学术成果。

🌐 **在线访问**: [https://123caiji.github.io](https://123caiji.github.io)

## 🌟 特性

- **现代化设计**: 采用最新的设计趋势，简洁美观
- **完全响应式**: 支持桌面、平板和移动设备
- **交互丰富**: 包含平滑滚动、动画效果和交互功能
- **易于定制**: 模块化设计，便于修改和扩展
- **SEO友好**: 优化的HTML结构和元数据
- **快速加载**: 优化的代码和资源加载

## 📁 文件结构

```
├── index.html          # 主页面文件
├── styles.css          # 样式文件
├── script.js           # JavaScript交互功能
├── README.md           # 项目说明文档
└── .gitignore          # Git忽略文件
```

## 🚀 快速开始

### 1. 克隆或下载项目

```bash
git clone <your-repository-url>
cd academic-homepage
```

### 2. 自定义内容

编辑 `index.html` 文件，替换以下内容：

- **个人信息**: 姓名、职位、联系方式
- **研究领域**: 专业领域和研究兴趣
- **发表论文**: 论文列表和链接
- **个人照片**: 替换占位符图片

### 3. 本地预览

直接在浏览器中打开 `index.html` 文件，或使用本地服务器：

```bash
# 使用Python
python -m http.server 8000

# 使用Node.js
npx serve .

# 使用PHP
php -S localhost:8000
```

### 4. 部署到GitHub Pages

1. 将代码推送到GitHub仓库 `123caiji/123caiji.github.io`
2. 在仓库设置中启用GitHub Pages
3. 选择源分支（通常是main或master）
4. 访问 [https://123caiji.github.io](https://123caiji.github.io)

**注意**: 由于仓库名是 `123caiji.github.io`，GitHub会自动将其识别为个人主页仓库。

## 🎨 自定义指南

### 修改颜色主题

在 `styles.css` 中修改CSS变量：

```css
:root {
    --primary-color: #4f46e5;    /* 主色调 */
    --secondary-color: #7c3aed;  /* 辅助色 */
    --accent-color: #fbbf24;     /* 强调色 */
    --text-color: #1f2937;       /* 文字颜色 */
    --bg-color: #ffffff;         /* 背景颜色 */
}
```

### 添加新的部分

1. 在HTML中添加新的section
2. 在CSS中添加对应样式
3. 在导航菜单中添加链接
4. 在JavaScript中添加滚动监听

### 修改动画效果

在 `script.js` 中可以调整：
- 滚动动画速度
- 数字计数动画
- 页面加载动画
- 鼠标悬停效果

## 📱 响应式设计

网站支持以下断点：
- **桌面**: 1200px+
- **平板**: 768px - 1199px
- **手机**: 320px - 767px

## 🔧 技术栈

- **HTML5**: 语义化标记
- **CSS3**: Flexbox、Grid、动画
- **JavaScript ES6+**: 现代JavaScript特性
- **Font Awesome**: 图标库
- **Google Fonts**: 字体库

## 📋 功能列表

### 导航功能
- [x] 固定导航栏
- [x] 移动端汉堡菜单
- [x] 平滑滚动
- [x] 当前页面高亮

### 首页部分
- [x] 个人介绍
- [x] 职业描述
- [x] 社交链接
- [x] 个人照片展示

### 关于我部分
- [x] 个人简介
- [x] 技能标签
- [x] 统计数据动画

### 研究部分
- [x] 研究领域卡片
- [x] 悬停动画效果
- [x] 图标展示

### 发表论文部分
- [x] 论文列表
- [x] 年份标签
- [x] 下载链接

### 联系方式部分
- [x] 联系信息
- [x] 联系表单
- [x] 表单验证

### 交互功能
- [x] 滚动动画
- [x] 数字计数动画
- [x] 回到顶部按钮
- [x] 通知系统
- [x] 表单提交处理

## 🎯 使用建议

### 内容建议
1. **保持简洁**: 突出最重要的信息
2. **定期更新**: 及时更新论文和项目信息
3. **高质量图片**: 使用清晰的专业照片
4. **联系方式**: 确保所有联系方式有效

### SEO优化
1. 添加适当的meta标签
2. 使用语义化HTML结构
3. 优化图片alt属性
4. 添加结构化数据

### 性能优化
1. 压缩图片文件
2. 使用CDN加载外部资源
3. 启用浏览器缓存
4. 优化CSS和JavaScript

## 🔗 相关链接

- [Font Awesome图标库](https://fontawesome.com/)
- [Google Fonts](https://fonts.google.com/)
- [GitHub Pages文档](https://pages.github.com/)
- [响应式设计指南](https://web.dev/responsive-web-design-basics/)

## 📄 许可证

MIT License - 详见 [LICENSE](LICENSE) 文件

## 🤝 贡献

欢迎提交Issue和Pull Request来改进这个项目！

## 📞 支持

如果您在使用过程中遇到问题，请：
1. 查看本文档的常见问题部分
2. 在GitHub上提交Issue
3. 联系项目维护者

---

## 🚀 快速部署

### 方法一：直接推送到GitHub
```bash
# 克隆仓库
git clone https://github.com/123caiji/123caiji.github.io.git
cd 123caiji.github.io

# 添加你的文件
# 编辑 index.html, styles.css, script.js 等文件

# 提交并推送
git add .
git commit -m "Update personal homepage"
git push origin main
```

### 方法二：使用GitHub Actions自动部署
项目已配置GitHub Actions工作流，每次推送到main分支时会自动部署到GitHub Pages。

### 方法三：本地预览
```bash
# 安装依赖
npm install

# 启动本地服务器
npm start
# 或
npm run dev
```

## 📊 项目统计

- **总文件数**: 8个核心文件
- **代码行数**: 1000+ 行
- **支持设备**: 桌面、平板、手机
- **浏览器支持**: Chrome, Firefox, Safari, Edge
- **加载速度**: < 2秒

## 🔗 相关链接

- **GitHub仓库**: [123caiji/123caiji.github.io](https://github.com/123caiji/123caiji.github.io)
- **在线演示**: [https://123caiji.github.io](https://123caiji.github.io)
- **问题反馈**: [Issues](https://github.com/123caiji/123caiji.github.io/issues)

---

**注意**: 这是一个模板项目，请根据您的实际需求进行定制。记得替换所有占位符内容，包括个人信息、照片和链接。
