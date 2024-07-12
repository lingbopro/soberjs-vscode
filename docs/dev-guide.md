# 开发指南

## 目录

- [开发指南](#开发指南)
  - [目录](#目录)
  - [项目结构](#项目结构)

## 项目结构

- [CHANGELOG.md](./../CHANGELOG.md): 存储版本更新记录
- [CONTRIBUTING.md](./../CONTRIBUTING.md): 包含贡献指南
- [custom-data/](./../custom-data/): 包含自定义 HTML 和 CSS 数据
  - [components.css-data.json](./../custom-data/components.css-data.json): 包含组件的 CSS 变量数据
  - [components.html-data.json](./../custom-data/components.html-data.json): 包含组件标签和属性数据
  - [global.css-data.json](./../custom-data/global.css-data.json): 包含全局 CSS 变量数据
- [docs/](./../docs/): 包含文档
  - [dev-guide.md](./../docs/dev-guide.md): 开发指南（此文件）
- [icon.png](./../icon.png): 此扩展的图标
- [LICENSE](./../LICENSE): 包含开源许可文件
- [package.json](./../package.json): 包含项目元数据
- [README.md](./../README.md): 自述文件
- [snippets/](./../snippets/): 包含代码片段文件
  - [html.code-snippets](./../snippets/html.code-snippets): 包含 HTML 代码片段
  - [js-ts.code-snippets](./../snippets/js-ts.code-snippets): 包含 JavaScript/Typescript 代码片段
- [SUPPORT.md](./../SUPPORT.md): 包含支持信息

## 贡献

见 [贡献指南](./../CONTRIBUTING.md)。

<!-- 没做完呢，别动！ -->
<!--

## 提示

### 生成 SVG 代码片段文件
<details>
<summary>点击展开</summary>

Sober 图标库中有很多图标，手动编写代码片段非常费时，因此可以使用脚本来生成。

1. 打开 [Sober.js 图标库](https://soberjs.com/resource/icon)
2. 打开 DevTools，并切换到 Console (控制台) 选项卡
3. 粘贴以下代码并运行
    **（运行时不要操作网页！！！）**

    <details>
    <summary>点击展开</summary>

    ```js
    下个版本补充，别动这！！！
    --- @lingbopro, 2024/7/12
    ```
    （脚本由 [@lingbopro](https://github.com/lingbopro) 制作）

    </details>

4. 等待 15-30 秒后，控制台会输出两段长文本，将第一段放入 [snippets/s-icon.code-snippets](./../snippets/s-icon.code-snippets) 中，第二段放入 [snippets/svg-icon.code-snippets](./../snippets/svg-icon.code-snippets) 中，并格式化它们

</details>
-->
