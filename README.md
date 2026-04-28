# 陶俊辉的个人主页 · Personal Portfolio

> GitHub Pages 部署的个人展示网页，基于纯 HTML / CSS / JS 构建，无需任何框架依赖。

## 🚀 快速部署到 GitHub Pages

### 第一步：新建仓库
1. 登录 GitHub，点击右上角 **+** → **New repository**
2. 仓库名填写：`<你的用户名>.github.io`（如 `sunq821-byte.github.io`）
3. 可见性选 **Public**
4. **不要**勾选 Initialize with README（因为本地已有文件）
5. 点击 **Create repository**

### 第二步：推送到 GitHub

在 `D:/24402/myWeb_GitHub/` 目录下执行：

```bash
git init
git add .
git commit -m "feat: 初始化个人主页"
git branch -M main
git remote add origin https://github.com/sunq821-byte/sunq821-byte.github.io.git
git push -u origin main
```

### 第三步：启用 GitHub Pages
1. 进入仓库 **Settings** → **Pages**
2. Source 选择 **Deploy from a branch**
3. Branch 选 **main** / `(root)`
4. 点击 **Save**

几分钟后访问：`https://sunq821-byte.github.io`

---

## 📁 文件结构

```
myWeb_GitHub/
├── index.html        # 主页（单文件，全部样式和脚本内联）
└── README.md         # 本说明文档
```

## ✏️ 待完善内容

以下信息在 `index.html` 中已留有占位区域，后续直接搜索注释填写：

| 区域 | 位置标记 | 说明 |
|------|---------|------|
| 项目经历 2、3 | `placeholder` 卡片 | 复制示例结构，填入项目名/描述/技术栈/链接 |
| 博客 / 技术文章 | `04 · More` 节 | 填入个人博客或掘金/CSDN 链接 |
| LeetCode 刷题 | `04 · More` 节 | 填入 LeetCode 主页链接及题量 |
| 比赛 / 奖项 | `04 · More` 节 | 填入参赛经历或所获证书 |
| 简历下载 | `04 · More` 节 | 上传 PDF 到仓库后填写相对路径 |
| 项目 GitHub 链接 | 每个 `project-card` | 将 `href="#"` 替换为实际仓库地址 |

## 🎨 设计说明

- **美学方向**：工业极简 × 代码感，深色主调（OKLCH 色彩空间）
- **主题色**：暖橙 `oklch(72% 0.19 55)` 
- **字体**：Fraunces（展示标题）+ Outfit（正文）+ JetBrains Mono（代码/标签）
- **响应式**：移动端汉堡菜单，断点 768px / 480px
- **无障碍**：语义化 HTML，ARIA 标签，键盘导航支持

## 📋 后续优化建议

- [ ] 添加 `favicon.ico`
- [ ] 添加 Open Graph meta 标签（微信/微博分享预览）
- [ ] 补全项目截图（可放在 `/assets/` 目录）
- [ ] 添加 Google Analytics（可选）
- [ ] 配置自定义域名（需购买域名）
