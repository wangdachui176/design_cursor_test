# 资源清单

## Figma 设计稿

- **链接**：https://www.figma.com/design/Fq5RnfDL8If87V9RQH5Rmg/✨AI搜索?node-id=836-74898
- **说明**：以 **homepage** 及组件/变体为准；样式、尺寸、Auto Layout 以设计稿为准。

## 变量与 Token

- **本包内路径**：
  - 原始变量：`spec/variables/figma-variables.json`
  - 扁平 Token：`spec/01-tokens.json`。

## 图标 SVG

- **本包内**：`spec/icons/搜索.svg`、`spec/icons/AI搜索.svg`；根目录 `assets/` 下亦有拷贝。

## APP 图标（WebP）

- **本包内**：`spec/app-icons-list.json` 为文件名列表。
- **项目内路径**（实现时）：`public/app-icons/<文件名>.webp`，文件名与列表一致（含中文与空格，URL 需 encode）。

## 站点信息

- **标题**：✨ AI搜索。
- **PWA**：`short_name` / `name` 可为「AI搜索」/「✨ AI搜索」。
