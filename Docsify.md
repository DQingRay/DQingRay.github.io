# Docsify 的安装与配置

## 安装

- 安装Node.js
- 安装docsify
```bash
npm i docsify-cli -g
```
- 选定文件夹，初始化
```bash
docsify init
```
- 开启本地测试
```bash
docsify serve
```

## 配置

### 文件结构

- `index.html` 主文件
- `README.md` 主页
- `.nojekyll` 防止Github忽略下划线开头的文件
- `_coverpage.md` 封面
- `_navbar.md` 右上角导航栏，大的导航更新在这里
- `_sidebar.md` 侧边栏，文件列表更新在这里

### 具体配置

见文件内容

## Git管理
建立空的DQingRay.github.io仓库
git init
git commit -m "first commit"
git remote add origin https://github.com/DQingRay/DQingRay.github.io.git
git push -u origin master