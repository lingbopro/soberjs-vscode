<h1>Sober.js for VSCode</h1>
<p>
  <a href="https://github.com/lingbopro/soberjs-vscode" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-black?style=for-the-badge&logo=github" alt="GitHub"/>
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=lingbopro.soberjs-vscode" target="_blank">
    <!-- Simpleicons 的 Microsoft 图标全寄了，只能用 SVG 凑合了 -->
    <img src="https://img.shields.io/badge/Visual%20Studio%20Marketplace-blue?style=for-the-badge&logo=data%3Aimage%2Fsvg%2Bxml%3Bcharset%3Dutf-8%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMjggMTI4Ij48cGF0aCBmaWxsPSIjZmZmZmZmIiBkPSJNOTQuMTQ1LjM0OGE4IDggMCAwIDAtLjU2My4wNzIgOCA4IDAgMCAwLS45MjguMDI3IDggOCAwIDAgMC0uOTgyLjIxNSA4IDggMCAwIDAtLjU1My4wNzIgOCA4IDAgMCAwLS44MjIuMzg3IDggOCAwIDAgMC0uNDg2LjIyOUE4IDggMCAwIDAgODggMi42NjhMNDUuNDg2IDQ5LjY3NGwtMjQuODItMjAuMzQtMi4xNzItMS44NjVhNS4zMzMgNS4zMzMgMCAwIDAtLjgyNi0uNDYzIDUuMzMzIDUuMzMzIDAgMCAwLS41MzUtLjMgNS4zMzMgNS4zMzMgMCAwIDAtLjYwNC0uMjI3IDUuMzMzIDUuMzMzIDAgMCAwLS42NDQtLjE1IDUuMzMzIDUuMzMzIDAgMCAwLS41MDQtLjAxNyA1LjMzMyA1LjMzMyAwIDAgMC0uNTEtLjA3NCA1LjMzMyA1LjMzMyAwIDAgMC0uMjY2LjA2IDUuMzMzIDUuMzMzIDAgMCAwLS4yMTQtLjAwMyA1LjMzMyA1LjMzMyAwIDAgMC0uMjI3LjA2IDUuMzMzIDUuMzMzIDAgMCAwLS40ODQuMDA2IDMuNCAzLjQgMCAwIDAtLjcwNy4yNGwtOS42OTQgNC4wNjdhNS4zMzMgNS4zMzMgMCAwIDAtMS40NjYuOTUgNS4zMzMgNS4zMzMgMCAwIDAtLjIxNS4xNzcgNS4zMzMgNS4zMzMgMCAwIDAtLjIzLjMxMiA1LjMzMyA1LjMzMyAwIDAgMC0uNjQuODggNS4zMzMgNS4zMzMgMCAwIDAtLjI2Ny40NzYgNS4zMzMgNS4zMzMgMCAwIDAtLjA5LjI3NSA1LjMzMyA1LjMzMyAwIDAgMC0uMjMyLjkwOCA1LjMzMyA1LjMzMyAwIDAgMC0uMTM5LjUxNnY1Ny42OGE1LjMzMyA1LjMzMyAwIDAgMCAuMTM5LjUxMiA1LjMzMyA1LjMzMyAwIDAgMCAuMjMyLjkxNCA1LjMzMyA1LjMzMyAwIDAgMCAuMDkuMjcxIDUuMzMzIDUuMzMzIDAgMCAwIC4yNjguNDc3IDUuMzMzIDUuMzMzIDAgMCAwIC42MzguODc5IDUuMzMzIDUuMzMzIDAgMCAwIC4yMy4zMTIgNS4zMzMgNS4zMzMgMCAwIDAgLjIxNi4xNzggNS4zMzMgNS4zMzMgMCAwIDAgMS40NjYuOTQ5bDkuNjk0IDQuMDY2YTUuMzMzIDUuMzMzIDAgMCAwIDEuNzE2LjM3IDUuMzMzIDUuMzMzIDAgMCAwIC41MS0uMDEgNS4zMzMgNS4zMzMgMCAwIDAgMS4yNzItLjE5OCA1LjMzMyA1LjMzMyAwIDAgMCAuNTEtLjE1NCA1LjMzMyA1LjMzMyAwIDAgMCAxLjUxMy0uODczbDIuMTcyLTEuODY3IDI0LjgyLTIwLjM0TDg4IDEyNS4zMzRhOCA4IDAgMCAwIDEuOTAyIDEuMzg3IDggOCAwIDAgMCAuNjA0LjIzIDggOCAwIDAgMCAuMDA2LjAwMiA4IDggMCAwIDAgMS4zNDIuNTE2IDggOCAwIDAgMCAuMjQyLjAxMyA4IDggMCAwIDAgMS41NTguMDg4IDggOCAwIDAgMCAuOTkuMDE0IDggOCAwIDAgMCAyLjQ1LS43MDNsMjYuMzczLTEyLjY4YTggOCAwIDAgMCAuNTcyLS4zMDYgOCA4IDAgMCAwIC4xNy0uMTA2IDggOCAwIDAgMCAuMzgzLS4yNSA4IDggMCAwIDAgLjE4MS0uMTM1IDggOCAwIDAgMCAuMzMtLjI1OCA4IDggMCAwIDAgLjIwNC0uMTczIDggOCAwIDAgMCAuMjc3LS4yNiA4IDggMCAwIDAgLjE5LS4xOSA4IDggMCAwIDAgLjI4My0uMzE0IDggOCAwIDAgMCAuMTQ0LS4xNjYgOCA4IDAgMCAwIC4yNjYtLjM1MiA4IDggMCAwIDAgLjE0Mi0uMTkzIDggOCAwIDAgMCAuMzMtLjUzIDggOCAwIDAgMCAuMDktLjE3IDggOCAwIDAgMCAuMi0uMzg2IDggOCAwIDAgMCAuMTEzLS4yNTYgOCA4IDAgMCAwIC4xNTItLjM3OSA4IDggMCAwIDAgLjA3Ni0uMjE1IDggOCAwIDAgMCAuMTE2LS4zNjcgOCA4IDAgMCAwIC4wODItLjMwNCA4IDggMCAwIDAgLjA3Mi0uMzQyIDggOCAwIDAgMCAuMDUzLS4yNzQgOCA4IDAgMCAwIC4wNTYtLjQzMSA4IDggMCAwIDAgLjAyMi0uMTggOCA4IDAgMCAwIC4wMDItLjAyMyA4IDggMCAwIDAgLjAyNy0uNjUzVjIxLjAyN2E4IDggMCAwIDAgMC0uMDExIDggOCAwIDAgMC0uMDI3LS42NTUgOCA4IDAgMCAwLS4wMTgtLjE1OCA4IDggMCAwIDAtLjA2Ni0uNTA4IDggOCAwIDAgMC0uMDM0LS4xNyA4IDggMCAwIDAtLjA5NS0uNDQzIDggOCAwIDAgMC0uMDczLS4yNjggOCA4IDAgMCAwLS4xMDMtLjMzIDggOCAwIDAgMC0uMTAyLS4yOTUgOCA4IDAgMCAwLS4xNDItLjM0NSA4IDggMCAwIDAtLjEtLjIzMyA4IDggMCAwIDAtLjIwOS0uNDA0IDggOCAwIDAgMC0uMTAzLS4xOTUgOCA4IDAgMCAwLS4zMzItLjUyOCA4IDggMCAwIDAtLjEwNi0uMTQgOCA4IDAgMCAwLS4yNzctLjM3IDggOCAwIDAgMC0uMTg4LS4yMTYgOCA4IDAgMCAwLS4yNDYtLjI3NCA4IDggMCAwIDAtLjE5My0uMTkzIDggOCAwIDAgMC0uMjgtLjI2MiA4IDggMCAwIDAtLjIwMi0uMTc0IDggOCAwIDAgMC0uMzMtLjI1NyA4IDggMCAwIDAtLjE4Mi0uMTM1IDggOCAwIDAgMC0uMzgzLS4yNSA4IDggMCAwIDAtLjE3LS4xMDYgOCA4IDAgMCAwLS41NzItLjMwNkw5Ny4wOTQgMS4xMkE4IDggMCAwIDAgOTQuNzUuNDE2YTggOCAwIDAgMC0uMzQyLjAwMiA4IDggMCAwIDAtLjI2My0uMDd6TTk2IDM2LjkwOHY1NC4xODZMNjIuOTQ3IDY0LjAwMiA5NiAzNi45MDh6bS04MCA4LjgyIDE2LjUyNyAxOC4yNzRMMTYgODIuMjc1VjQ1LjczeiIvPjwvc3ZnPg%3D%3D" alt="GitHub"/>
  </a>
</p>
<p>
  <a href="https://github.com/lingbopro/soberjs-vscode/releases" target="_blank">
    <img src="https://img.shields.io/github/v/release/lingbopro/soberjs-vscode.svg?style=for-the-badge" alt="Release"/>
  </a>
  <a href="https://github.com/lingbopro/soberjs-vscode/actions?query=workflow:CI" target="_blank">
    <img src="https://img.shields.io/github/actions/workflow/status/lingbopro/soberjs-vscode/CI.yml?style=for-the-badge" alt="Build Status"/>
  </a>
  <a href="https://marketplace.visualstudio.com/items?itemName=lingbopro.soberjs-vscode" target="_blank">
    <img src="https://img.shields.io/visual-studio-marketplace/i/lingbopro.soberjs-vscode?style=for-the-badge&logo=visualstudiocode&label=Installs" alt="Visual Studio Marketplace Installs" />
    <img src="https://img.shields.io/visual-studio-marketplace/r/lingbopro.soberjs-vscode?style=for-the-badge&logo=visualstudiocode&label=Rating" alt="Visual Studio Marketplace Rating" />
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
- CSS 变量名和枚举值
- 一点 HTML 代码片段
- Material 图标 SVG 补全

目前已支持 Sober.js 0.2.15 的所有组件和 CSS 变量（见下表）  

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
  - [x] 选择框 Picker
  - [x] 分割线 Divider
- [x] 容器
  - [x] 页面 Page
  - [x] 抽屉 Drawer
  - [x] 滚动 Scroll View
  - [x] 卡片 Card
  - [x] 搜索栏 Search
  - [x] 轮播图 Carousel
- [x] 导航
  - [x] 选项卡 Tab
  - [x] 导航栏 Navigation
  - [x] 应用栏 Appbar
- [x] 部件
  - [x] 对话框 Dialog
  - [x] 弹出框 Popup
  - [x] 弹出式菜单 Popup Menu
  - [x] 提示框 Snackbar
  - [x] 工具提示 Tooltip
  - [x] 徽章 Badge
  - [x] 纸片 Chip
- [x] 数据
  - [x] 表格 Table

</details>
<details>
  <summary>支持的 CSS 变量</summary>

- [x] 组件变量
  - [x] 波纹 Ripple
    - [x] `--ripple-color`
    - [x] `-ripple-opacity`
  - [x] 文本框 Text Field / 选择框 Picker
    - [x] `--border-radius`
    - [x] `--border-width`
    - [x] `--border-color`
    - [x] `--padding`
- [x] 全局变量

  <details>
  <summary>点击展开（共 68 个）</summary>

  - [x] `--s-color-primary`
  - [x] `--s-color-on-primary`
  - [x] `--s-color-primary-container`
  - [x] `--s-color-on-primary-container`
  - [x] `--s-color-secondary`
  - [x] `--s-color-on-secondary`
  - [x] `--s-color-secondary-container`
  - [x] `--s-color-on-secondary-container`
  - [x] `--s-color-tertiary`
  - [x] `--s-color-on-tertiary`
  - [x] `--s-color-tertiary-container`
  - [x] `--s-color-on-tertiary-container`
  - [x] `--s-color-error`
  - [x] `--s-color-on-error`
  - [x] `--s-color-error-container`
  - [x] `--s-color-on-error-container`
  - [x] `--s-color-background`
  - [x] `--s-color-on-background`
  - [x] `--s-color-outline`
  - [x] `--s-color-outline-variant`
  - [x] `--s-color-surface`
  - [x] `--s-color-on-surface`
  - [x] `--s-color-surface-variant`
  - [x] `--s-color-on-surface-variant`
  - [x] `--s-color-inverse-surface`
  - [x] `--s-color-inverse-on-surface`
  - [x] `--s-color-inverse-primary`
  - [x] `--s-color-surface-container`
  - [x] `--s-color-surface-container-high`
  - [x] `--s-color-surface-container-highest`
  - [x] `--s-color-surface-container-low`
  - [x] `--s-color-surface-container-lowest`
  - [x] `--s-color-dark-primary`
  - [x] `--s-color-dark-on-primary`
  - [x] `--s-color-dark-primary-container`
  - [x] `--s-color-dark-on-primary-container`
  - [x] `--s-color-dark-secondary`
  - [x] `--s-color-dark-on-secondary`
  - [x] `--s-color-dark-secondary-container`
  - [x] `--s-color-dark-on-secondary-container`
  - [x] `--s-color-dark-tertiary`
  - [x] `--s-color-dark-on-tertiary`
  - [x] `--s-color-dark-tertiary-container`
  - [x] `--s-color-dark-on-tertiary-container`
  - [x] `--s-color-dark-error`
  - [x] `--s-color-dark-on-error`
  - [x] `--s-color-dark-error-container`
  - [x] `--s-color-dark-on-error-container`
  - [x] `--s-color-dark-background`
  - [x] `--s-color-dark-on-background`
  - [x] `--s-color-dark-outline`
  - [x] `--s-color-dark-outline-variant`
  - [x] `--s-color-dark-surface`
  - [x] `--s-color-dark-on-surface`
  - [x] `--s-color-dark-surface-variant`
  - [x] `--s-color-dark-on-surface-variant`
  - [x] `--s-color-dark-inverse-surface`
  - [x] `--s-color-dark-inverse-on-surface`
  - [x] `--s-color-dark-inverse-primary`
  - [x] `--s-color-dark-surface-container`
  - [x] `--s-color-dark-surface-container-high`
  - [x] `--s-color-dark-surface-container-highest`
  - [x] `--s-color-dark-surface-container-low`
  - [x] `--s-color-dark-surface-container-lowest`
  - [x] `--s-elevation-level1`
  - [x] `--s-elevation-level2`
  - [x] `--s-elevation-level3`
  - [x] `--s-elevation-level4`
  - [x] `--s-elevation-level5`

  </details>
</details>

### 功能展示

还没弄（（（  

## Release Notes

见 [版本说明](./CHANGELOG.md)  

## To-do

- [x] 支持更多组件
- [ ] 完善悬停提示
- [x] 完成 CSS 变量名和枚举值补全
- [x] 增加 SVG 图标补全
- [ ] 使 SVG 图标补全可以补全填充图标，不仅是线条图标

