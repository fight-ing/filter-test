# 🚀 快速部署指南

## 📦 文件清单

确保你有以下文件:
- ✅ `index.html` - 主页面
- ✅ `README.md` - 项目说明
- ✅ `.gitignore` - Git忽略配置

---

## 🎯 部署步骤(3分钟完成)

### 步骤1: 创建GitHub仓库

1. 打开 https://github.com/new
2. 填写仓库信息:
   - Repository name: `mobile-filter-system`
   - Description: `移动端筛选系统原型`
   - 选择 `Public` (公开)
   - ❌ 不要勾选 "Add a README file"
3. 点击 `Create repository`

### 步骤2: 上传文件

**方式A: 网页上传(最简单)**

1. 在新建的仓库页面,点击 `uploading an existing file`
2. 拖拽以下3个文件到页面:
   - `index.html`
   - `README.md`
   - `.gitignore`
3. 在底部填写提交信息: `Initial commit`
4. 点击 `Commit changes`

**方式B: Git命令行**

```bash
# 克隆仓库到本地
git clone https://github.com/你的用户名/mobile-filter-system.git
cd mobile-filter-system

# 复制文件到仓库目录
# (把下载的index.html, README.md, .gitignore复制进来)

# 提交并推送
git add .
git commit -m "Initial commit"
git push origin main
```

### 步骤3: 开启GitHub Pages

1. 进入仓库页面
2. 点击顶部的 `Settings` (设置)
3. 左侧菜单找到 `Pages`
4. 在 `Source` 下:
   - Branch: 选择 `main`
   - Folder: 选择 `/ (root)`
5. 点击 `Save`
6. 等待1-2分钟,页面顶部会显示:
   ```
   ✅ Your site is live at https://你的用户名.github.io/mobile-filter-system/
   ```

### 步骤4: 访问你的页面

在手机浏览器打开:
```
https://你的用户名.github.io/mobile-filter-system/
```

---

## 📱 手机访问方式

### 方式1: 直接输入网址
- 在手机浏览器输入上面的链接

### 方式2: 生成二维码
1. 访问 https://cli.im/ (草料二维码)
2. 输入你的GitHub Pages链接
3. 生成二维码
4. 手机扫码访问

### 方式3: 短链接
1. 访问 https://bit.ly/
2. 输入GitHub Pages链接
3. 生成短链接,方便分享

---

## 🔧 常见问题

### Q1: 页面显示404
**原因**: Pages部署需要时间
**解决**: 等待2-5分钟后刷新

### Q2: 看不到最新更新
**原因**: 浏览器缓存
**解决**: 
- 手机浏览器: 清除缓存后重新访问
- 或在链接后加版本号: `?v=2`

### Q3: 需要修改代码
**方法**:
1. 在GitHub网页上点击 `index.html`
2. 点击编辑按钮(铅笔图标)
3. 修改代码
4. 点击 `Commit changes`
5. 等待1分钟,刷新页面即可看到更新

### Q4: 想自定义域名
**步骤**:
1. 购买域名(如 filter.yourdomain.com)
2. 在域名DNS设置中添加CNAME记录:
   ```
   CNAME  filter  你的用户名.github.io
   ```
3. 在GitHub Pages设置中添加自定义域名

---

## 🎨 快速修改

### 改主题色(#007AFF → 你的颜色)

1. 点击 `index.html` 进行编辑
2. 使用浏览器搜索功能(Ctrl/Cmd+F)查找 `#007AFF`
3. 全部替换为你想要的颜色,例如:
   - `#FF3B30` (红色)
   - `#34C759` (绿色)
   - `#FF9500` (橙色)
4. 提交更改

### 改品类图标

找到这段代码:
```html
<div class="category-icon">👜</div>
<div class="category-name">手袋</div>
```
替换图标 emoji 即可。

[Emoji参考](https://emojipedia.org/)

---

## 📊 访问统计

想查看页面访问量?

### 添加Google Analytics
1. 注册 Google Analytics
2. 获取跟踪代码
3. 在 `index.html` 的 `</head>` 前添加跟踪代码

### 或使用简单计数器
在 `index.html` 底部添加:
```html
<script src="https://cdn.counter.dev/script.js"></script>
```

---

## 🎉 完成!

现在你有了一个:
- ✅ 可在线访问的移动端筛选原型
- ✅ 可随时编辑更新的源代码
- ✅ 可分享给团队成员的链接
- ✅ 完全免费的托管服务

**下一步建议**:
1. 用真实数据替换演示内容
2. 根据业务需求调整筛选项
3. 收集用户反馈进行优化
4. 考虑转为正式开发项目

---

有问题? 
- GitHub Issues: 在仓库中提Issue
- Email: 联系项目负责人
