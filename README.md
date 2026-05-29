# 买家秀图库

一个基于 HTML5 的买家秀图片展示系统，支持图库浏览、随机展示和图片分享功能。

## 🎯 功能特点

### 📷 图库浏览 (index.html)
- 瀑布流布局展示所有图片
- 图片懒加载，优化性能
- 点击图片进入详情页
- 响应式设计，支持 PC 和移动端

### 🔗 图片详情 (image.html)
- 独立页面展示单张图片
- 支持上一张/下一张导航
- 📋 一键复制分享链接
- � 移动端原生分享功能
- URL 参数分享（`?id=123`）

### 🎲 随机展示 (random.html)
- 点击按钮随机展示图片
- 自动预加载，流畅切换
- 显示当前图片序号

### ✨ 通用特性
- 精美的渐变 UI 设计
- 移动端汉堡菜单导航
- 统一的顶部导航栏
- ⚠️ 包含免责声明

## 📦 项目结构

```
.
├── index.html          # 图库首页（瀑布流展示）
├── image.html          # 图片详情页（支持分享）
├── random.html         # 随机展示页
├── README.md           # 项目说明文档
└── src/                # 图片文件夹
    ├── api.1ove.icu (1).jpg
    ├── api.1ove.icu (2).jpg
    └── ...
```

## 🚀 部署到 GitHub Pages

### 推送代码

```bash
# 添加所有文件
git add .

# 提交更改
git commit -m "Update project"

# 推送到 GitHub
git push
```

### 启用 GitHub Pages

1. 在 GitHub 仓库页面，点击 **Settings**
2. 在左侧菜单找到 **Pages**
3. 在 **Build and deployment** 部分：
   - Source: 选择 **Deploy from a branch**
   - Branch: 选择 **main** 和 **/(root)**
4. 点击 **Save**

部署成功后访问：`https://你的用户名.github.io/仓库名/`

## 📱 页面说明

### 首页 - 图库浏览
访问根路径即可打开图库页面，浏览所有买家秀图片。

### 图片详情页
- 访问：`https://你的用户名.github.io/仓库名/image.html?id=123`
- 点击图库中的任意图片即可进入详情页
- 支持上一张/下一张切换
- 可复制分享链接或使用原生分享

### 随机展示页
- 访问：`https://你的用户名.github.io/仓库名/random.html`
- 每次点击按钮随机展示一张图片

## ⚙️ 自定义配置

### 修改图片数量

编辑 HTML 文件中的 `IMAGE_COUNT` 常量：

```javascript
const IMAGE_COUNT = 369;  // 修改为你的图片总数
```

### 修改图片文件夹路径

编辑 HTML 文件中的 `IMAGE_FOLDER` 常量：

```javascript
const IMAGE_FOLDER = 'images';  // 修改为你的图片文件夹路径
```

### 添加更多图片

按照文件名规则 `api.1ove.icu (数字).jpg` 添加图片到 `src` 文件夹，并更新 `IMAGE_COUNT`。

## 📝 注意事项

1. 图片文件命名必须遵循规则：`api.1ove.icu (数字).jpg`
2. 数字从 1 开始连续递增
3. 确保图片格式为 JPG
4. 部署到 GitHub Pages 时，注意 Git 对单个文件 25MB 的限制

## ⚠️ 免责声明

本站展示的图片均来源于互联网，仅供学习交流使用。我们不拥有这些图片的版权，所有版权归原作者所有。如有侵权，请联系我们删除。

## 📄 许可证

MIT License

---

**Enjoy! 🎉**
