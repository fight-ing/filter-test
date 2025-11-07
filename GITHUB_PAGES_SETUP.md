# GitHub Pages 部署指南

## 📝 快速部署步骤

### 方法一：通过 Pull Request（推荐）

1. **创建 Pull Request**
   - 访问仓库：https://github.com/fight-ing/filter-test
   - 点击 "Pull requests" 标签
   - 点击 "New pull request"
   - Base: `main` ← Compare: `claude/filter-sort-interaction-design-011CUt4QeZ6ddyDqrHhveDd9`
   - 点击 "Create pull request"
   - 填写标题："Add filter-sort interaction prototype"
   - 点击 "Create pull request"
   - 点击 "Merge pull request" → "Confirm merge"

2. **启用 GitHub Pages**
   - 进入仓库的 `Settings` 页面
   - 在左侧菜单找到 `Pages`
   - 在 "Build and deployment" 部分：
     - Source: 选择 `Deploy from a branch`
     - Branch: 选择 `main` 分支，目录选择 `/ (root)`
     - 点击 `Save`
   - 等待 1-2 分钟，页面顶部会显示绿色提示

3. **访问预览链接**
   - 链接将会是：https://fight-ing.github.io/filter-test/
   - 原型文件：https://fight-ing.github.io/filter-test/filter-sort-prototype.html

---

### 方法二：直接从当前分支启用（更快）

如果您想直接从当前特性分支发布：

1. **启用 GitHub Pages**
   - 进入仓库的 `Settings` 页面
   - 在左侧菜单找到 `Pages`
   - 在 "Build and deployment" 部分：
     - Source: 选择 `Deploy from a branch`
     - Branch: 选择 `claude/filter-sort-interaction-design-011CUt4QeZ6ddyDqrHhveDd9` 分支
     - 目录选择 `/ (root)`
     - 点击 `Save`

2. **访问预览链接**
   - 等待 1-2 分钟
   - 访问：https://fight-ing.github.io/filter-test/

---

## 📱 扫码预览

部署完成后，可以生成二维码让手机扫码预览：

1. 访问：https://www.the-qrcode-generator.com/
2. 输入您的 GitHub Pages 链接
3. 生成二维码并用手机扫描

---

## 🔍 检查部署状态

1. 进入仓库的 `Actions` 标签
2. 查看 "pages build and deployment" 工作流
3. 绿色勾号 ✓ = 部署成功
4. 红色叉号 ✗ = 部署失败（查看日志）

---

## 🎯 验证部署

部署成功后：

1. **桌面浏览器验证**
   - 访问 GitHub Pages 链接
   - 按 F12 打开开发者工具
   - 切换到移动设备模式（Ctrl+Shift+M）
   - 选择 iPhone 或 Android 设备

2. **手机真机验证**
   - 直接在手机浏览器输入链接
   - 测试所有交互功能

---

## 📋 可访问的文件

部署后，以下文件可直接访问：

- **主页**: https://fight-ing.github.io/filter-test/
- **原型**: https://fight-ing.github.io/filter-test/filter-sort-prototype.html
- **说明**: https://fight-ing.github.io/filter-test/README.md

---

## 💡 常见问题

**Q: 页面显示 404**
- 检查分支名称是否正确
- 确认文件已提交并推送
- 等待 1-2 分钟让 GitHub 构建完成

**Q: 页面样式错误**
- 清除浏览器缓存
- 强制刷新（Ctrl+Shift+R）

**Q: 如何更新页面**
- 修改文件后提交推送
- GitHub Pages 会自动重新部署
- 等待 1-2 分钟即可看到更新

---

## 🔒 私有仓库说明

如果仓库是私有的：
- 免费账户无法使用 GitHub Pages
- 需要升级到 GitHub Pro
- 或将仓库改为 Public

---

## 📧 分享链接

部署完成后，您可以直接分享以下链接给其他人：

```
🌐 在线预览: https://fight-ing.github.io/filter-test/
```

任何人都可以通过这个链接访问您的原型！
