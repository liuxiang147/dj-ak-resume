# DJ AK 个人简历网站

## 文件位置
`/Users/mr.ak/Documents/New OpenCode Project/dj-ak-resume/index.html`

## 功能特性
- 跨浏览器兼容（Chrome, Firefox, Safari, Edge, IE11+）
- 响应式设计（PC/平板/手机自适应）
- SEO优化（JSON-LD结构化数据 + Meta标签）
- 粒子动画背景
- 滚动动画效果
- 暗色科技风格

## 免费部署方式（推荐）

### 1. GitHub Pages（推荐）
```bash
cd dj-ak-resume
git init
git add .
git commit -m "DJ AK Resume"
git remote add origin https://github.com/你的用户名/dj-ak-resume.git
git push -u origin main
```
然后在 GitHub 仓库 Settings → Pages → 选择 main 分支即可。
访问地址：`https://你的用户名.github.io/dj-ak-resume/`

### 2. Netlify（最简单）
1. 打开 https://app.netlify.com
2. 直接把 `dj-ak-resume` 文件夹拖进去
3. 自动部署，获得链接

### 3. Vercel
1. 打开 https://vercel.com
2. 导入 GitHub 仓库
3. 自动部署

### 4. 直接打开本地文件
双击 `index.html` 即可在浏览器中预览

## 自定义修改

### 修改个人信息
编辑 `index.html` 中的内容：
- 技能百分比：搜索 `data-width="95"` 修改数字
- 工作经历：搜索 `timeline-content` 修改内容
- 联系方式：搜索 `contact-card` 修改链接

### 修改头像
在 `.image-frame` div 中替换 emoji 为你的照片：
```html
<div class="image-frame">
    <img src="你的照片.jpg" alt="DJ AK" style="width:100%;height:100%;object-fit:cover;">
</div>
```
