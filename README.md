<h1>Sober.js for VSCode</h1>
<p>
  <a href="https://github.com/lingbopro/soberjs-vscode" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=lingbopro.soberjs-vscode" target="_blank">
    <img src="https://img.shields.io/badge/Visual%20Studio%20Marketplace-blue?style=for-the-badge&logo=visualstudiocode" alt="GitHub"/>
  </a>
</p>
<p>
  <a href="https://github.com/lingbopro/soberjs-vscode/releases" target="_blank">
    <img src="https://img.shields.io/github/v/release/lingbopro/soberjs-vscode.svg?style=for-the-badge" alt="Release"/>
  </a>
  <a href="https://github.com/lingbopro/soberjs-vscode/actions?query=workflow:CI" target="_blank">
    <img src="https://img.shields.io/github/actions/workflow/status/lingbopro/soberjs-vscode/CI.yaml?style=for-the-badge" alt="Build status"/>
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=lingbopro.soberjs-vscode" target="_blank">
    <img src="https://img.shields.io/visual-studio-marketplace/i/lingbopro.soberjs-vscode?style=for-the-badge&logo=visualstudiocode&label=Installs" alt="Visual Studio Marketplace Installs" />
    <img src="https://img.shields.io/visual-studio-marketplace/r/lingbopro.soberjs-vscode?style=for-the-badge&logo=visualstudiocode&label=Rating" alt="Visual Studio Marketplace Rating" />
    <img src="https://img.shields.io/visual-studio-marketplace/v/lingbopro.soberjs-vscode?style=for-the-badge&logo=visualstudiocode&label=Version" alt="Visual Studio Marketplace Version" />
  </a>
</p>

## 介绍

一个 [Visual Studio Code](https://code.visualstudio.com) 扩展，为 [Sober.js 组件库](https://soberjs.com) 提供自动完成、悬停提示、代码片段等功能  

（非官方扩展，组件库由 [@apprat](https://gituhb.com/apprat) 创建和维护，此扩展由 [@lingbopro](https://github.com/lingbopro) 制作）  

## 安装

在 Visual Studio Code 的“扩展”页面下，搜索 `Sober.js` 并安装  
你也可以从 [Visual Studio Marketplace](https://marketplace.visualstudio.com/items?itemName=lingbopro.soberjs-vscode) 安装  

或者，你也可以从 [Release 页面](https://github.com/lingbopro/soberjs-vscode/releases) 下载 VSIX 文件，然后在 Visual Studio Code 中安装。  


## 功能

代码自动补全和悬停提示，包括：  

- HTML 标签名
- HTML 标签属性名称和枚举值
- _~~CSS 变量名和枚举值（尚未完成）~~_
- 一点 HTML 代码片段

目前已支持 15 个组件（见下表）  

<details>
  <summary>支持的组件（点击展开）</summary>

- [x] 基础组件
  - [x] 按钮 Button
  - [x] 图标 Icon
  - [x] 图标按钮 Icon Button
  - [x] 浮动操作按钮 FAB
  - [x] 分组按钮 Segmented
  - [x] 波纹 Ripple
  - [x] 复选框 Checkbox
  - [x] 单选按钮 Radio Button
  - [x] 滑块 Slider
  - [x] 线性进度 Linear Progress
  - [x] 圆形进度 Circular Progress
  - [x] 开关 Switch
  - [x] 文本框 Text Field
  - [x] 评分 Rate
  - [x] 分割线 Divider
- [ ] 容器
  - [ ] 页面 Page
  - [ ] 抽屉 Drawer
  - [ ] 滚动 Scroll View
  - [x] 卡片 Card
  - [ ] 搜索栏 Search
  - [ ] 轮播图 Carousel
- [ ] 导航
  - [ ] 选项卡 Tab
  - [ ] 导航栏 Navigation
  - [ ] 顶部应用栏 Top App Bar
- [ ] 部件
  - [x] 对话框 Dialog
  - [ ] 下拉框 Dropdown
  - [ ] 菜单 Menu
  - [ ] 提示框 Snackbar
  - [x] 工具提示 Tooltip
  - [x] 徽章 Badge
  - [ ] 纸片 Chip
- [ ] 数据
  - [ ] 表格 Table

</details>

### 功能展示

还没弄（（（  

## Release Notes

见 [版本说明](./CHANGELOG.md)  

## To-do

- [ ] 支持更多组件
- [ ] 完善悬停提示
- [ ] 完成 CSS 变量名和枚举值补全
- [ ] 增加 SVG 图标补全

