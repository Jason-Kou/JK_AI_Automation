# YouTube 视频文档集合

这是一个使用Jekyll和Minimal Mistakes主题构建的YouTube视频文档网站，部署在GitHub Pages上。

## 项目结构

```
youtube_web/
├── _config.yml             # Jekyll配置文件
├── Gemfile                 # Ruby依赖管理
├── index.html              # 主页（Jekyll格式）
├── _data/
│   └── navigation.yml      # 网站导航配置
├── _pages/                 # 页面文件
│   ├── about.md
│   ├── docs.md
│   ├── videos.md
│   └── warren-buffett.md
├── Warren Buffett 投资心法/ # 原始HTML文档（保留）
└── assets/                 # 静态资源
    └── images/
```

## 技术栈

- **Jekyll** - 静态网站生成器
- **Minimal Mistakes** - 专业的Jekyll主题
- **GitHub Pages** - 免费托管服务
- **Markdown** - 内容编写格式

## 当前主题

- **Warren Buffett 投资心法** - 深入了解股神巴菲特的投资理念和策略

## 如何部署到GitHub Pages

### 1. 推送代码到GitHub

```bash
# 如果还没有初始化git仓库
git init

# 添加所有文件
git add .

# 提交更改
git commit -m "Initial commit: Add YouTube documentation website"

# 添加远程仓库（替换为你的GitHub仓库URL）
git remote add origin https://github.com/你的用户名/你的仓库名.git

# 推送到GitHub
git push -u origin main
```

### 2. 启用GitHub Pages

1. 进入你的GitHub仓库页面
2. 点击 **Settings** 标签
3. 在左侧菜单中找到 **Pages**
4. 在 **Source** 部分选择 **Deploy from a branch**
5. 选择 **main** 分支和 **/ (root)** 文件夹
6. 点击 **Save**

### 3. 访问你的网站

几分钟后，你的网站将在以下地址可用：
```
https://你的用户名.github.io/你的仓库名/
```

## 添加新主题

当你有新的YouTube视频文档时：

1. 创建新的文件夹，命名为主题名称
2. 将HTML文档放入该文件夹
3. 编辑 `index.html`，在 `topics-grid` 中添加新的主题卡片：

```html
<div class="topic-card">
    <div class="topic-icon">🎯</div>
    <h3 class="topic-title">新主题标题</h3>
    <p class="topic-description">主题描述</p>
    <a href="新主题文件夹/文档文件.html" class="topic-link">
        查看文档
        <svg class="arrow-icon" viewBox="0 0 20 20" fill="currentColor">
            <path fill-rule="evenodd" d="M10.293 3.293a1 1 0 011.414 0l6 6a1 1 0 010 1.414l-6 6a1 1 0 01-1.414-1.414L14.586 11H3a1 1 0 110-2h11.586l-4.293-4.293a1 1 0 010-1.414z" clip-rule="evenodd" />
        </svg>
    </a>
</div>
```

4. 提交并推送更改到GitHub

## 特性

- 📱 响应式设计，支持移动设备
- 🎨 现代化UI设计
- ⚡ 快速加载
- 🔗 清晰的导航结构
- 🌟 交互式动画效果

## 技术栈

- HTML5
- CSS3 (Grid, Flexbox, 动画)
- 原生JavaScript
- Google Fonts (Inter字体)

## 许可证

本项目仅供学习参考使用。 