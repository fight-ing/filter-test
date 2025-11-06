# 移动端筛选系统 - iOS风格

一个专为移动端设计的商品筛选系统原型,采用iOS设计规范。

## 功能特性

- ✅ 品类宫格选择
- ✅ 客服多选(支持搜索、分组)
- ✅ 鉴定师单选(分组结构)
- ✅ 综合筛选(品牌、成色、状态等)
- ✅ 品牌二级页面(字母索引)
- ✅ 已选成员展示与移除
- ✅ 键盘适配优化
- ✅ 浮层设计不影响列表

## 在线预览

部署后访问: `https://你的用户名.github.io/仓库名/`

## 本地预览

```bash
# 直接用浏览器打开 index.html
# 或使用本地服务器:
python -m http.server 8000
```

## 技术栈

- 纯HTML/CSS/JavaScript
- 无任何框架依赖
- 移动端优先设计
- iOS风格交互

## 项目结构

```
.
├── index.html          # 主页面
├── README.md          # 项目说明
└── assets/            # 资源文件(如需要)
```

## 部署到GitHub Pages

### 方法1: 网页操作(推荐新手)

1. **创建GitHub仓库**
   - 登录 [GitHub](https://github.com)
   - 点击右上角 `+` → `New repository`
   - 仓库名: `mobile-filter-system` (或其他名称)
   - 选择 `Public`
   - 勾选 `Add a README file`
   - 点击 `Create repository`

2. **上传文件**
   - 进入仓库页面
   - 点击 `Add file` → `Upload files`
   - 拖拽 `index.html` 文件到页面
   - 点击 `Commit changes`

3. **开启GitHub Pages**
   - 进入仓库的 `Settings`
   - 左侧菜单找到 `Pages`
   - Source 选择 `Deploy from a branch`
   - Branch 选择 `main` + `/ (root)`
   - 点击 `Save`
   - 等待1-2分钟,页面会显示访问链接

4. **访问你的页面**
   - 链接格式: `https://你的用户名.github.io/仓库名/`
   - 用手机浏览器访问这个链接即可

### 方法2: Git命令行(开发者)

```bash
# 1. 克隆或初始化仓库
git init
git remote add origin https://github.com/你的用户名/仓库名.git

# 2. 添加文件
git add index.html README.md
git commit -m "Initial commit: Mobile filter system"

# 3. 推送到GitHub
git branch -M main
git push -u origin main

# 4. 在GitHub网页上开启Pages(同方法1的步骤3)
```

## 使用说明

### 品类筛选
- 点击图标选择品类
- 选择后自动确认并关闭

### 客服筛选(多选)
- 支持选择多个客服
- 顶部显示已选成员
- 点击 ✕ 可移除
- 支持搜索框实时过滤
- 点击"确定"应用筛选

### 鉴定师筛选(单选)
- 单选一个鉴定师
- 支持搜索框过滤
- 分组结构展示

### 综合筛选
- 品牌支持多选,点击"全部品牌"进入二级页
- 成色、状态等常规筛选
- 时间范围选择
- 底部"重置"/"确定"操作

## 自定义修改

### 修改主题色
在 `index.html` 中查找并替换:
```css
#007AFF  →  你的颜色代码
```

### 修改筛选项
在 HTML 中找到对应的 `filter-options` 区域,添加或删除:
```html
<div class="filter-option" onclick="selectFilterOption(this, 'type')">选项名称</div>
```

### 修改成员数据
在对应的 `member-item` 区域修改:
```html
<div class="member-item" onclick="selectStaff(this, '姓名')" data-name="姓名">
    ...
</div>
```

## 浏览器兼容性

- ✅ iOS Safari 12+
- ✅ Chrome Mobile 80+
- ✅ 微信内置浏览器
- ✅ Android WebView

## License

MIT License

## 联系方式

如有问题请提Issue
