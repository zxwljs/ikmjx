# 买家秀随机展示

一个基于 HTML5 的单页应用，用于随机展示买家秀图片。

## 🎯 功能特点

- 🎲 随机展示图片，每次点击按钮随机切换
- 📱 响应式设计，支持 PC 和移动端
- ✨ 精美的 UI 设计和动画效果
- 🔄 自动预加载图片，流畅切换
- 📊 显示当前图片序号和总数量
- ⚠️ 包含免责声明

## 📦 项目结构

```
.
├── index.html          # 主页面
├── README.md           # 项目说明文档
└── src/                # 图片文件夹
    ├── api.1ove.icu (1).jpg
    ├── api.1ove.icu (2).jpg
    └── ...
```

## 🚀 部署到 GitHub Pages

### 方法一：直接推送

```bash
# 添加所有文件
git add .

# 提交更改
git commit -m "Add image showcase app"

# 推送到 GitHub
git push
```

### 方法二：启用 GitHub Pages

1. 在 GitHub 仓库页面，点击 **Settings**
2. 在左侧菜单找到 **Pages**
3. 在 **Build and deployment** 部分：
   - Source: 选择 **Deploy from a branch**
   - Branch: 选择 **main** 和 **/(root)**
4. 点击 **Save**

部署成功后，访问 `https://你的用户名.github.io/仓库名/` 即可预览。

## ⚙️ 自定义配置

### 修改图片数量

编辑 [`index.html`](index.html) 文件中的 `IMAGE_COUNT` 常量：

```javascript
const IMAGE_COUNT = 369;  // 修改为你的图片总数
```

### 修改图片文件夹路径

如果你的图片不在 `src` 文件夹，修改 `IMAGE_FOLDER` 常量：

```javascript
const IMAGE_FOLDER = 'images';  // 修改为你的图片文件夹路径
```

### 添加更多图片

按照文件名规则 `api.1ove.icu (数字).jpg` 添加图片到 `src` 文件夹，并更新 `IMAGE_COUNT`。

## 📝 注意事项

1. 图片文件命名必须遵循规则：`api.1ove.icu (数字).jpg`
2. 数字从 1 开始连续递增
3. 确保图片格式为 JPG
4. 部署到 GitHub Pages 时，注意图片文件大小限制

## ⚠️ 免责声明

本站展示的图片均来源于互联网，仅供学习交流使用。我们不拥有这些图片的版权，所有版权归原作者所有。如有侵权，请联系我们删除。

## 📄 许可证

MIT License

## 🤝 贡献

欢迎提交 Issue 和 Pull Request！

---

**Enjoy! 🎉**
