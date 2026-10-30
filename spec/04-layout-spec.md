# 布局与尺寸规范

## Homepage 容器

- 宽度：394px，`box-sizing: border-box`。
- 布局：`column`，`align-items: center`，`gap: 34px`，`padding: 20px`。
- 背景：`#FFFFFF`。

## 搜索框/展开

- 布局：`column`，填满父级宽度（`align-self: stretch`）。
- 边框：1px 渐变（AI 渐变色），圆角 16px。
- 阴影：`0px 2px 20px 0px rgba(0, 0, 0, 0.04)`。
- 内层：`column`，`align-self: stretch`，`gap: 6px`，`padding: 6px 0 0`。

## 搜索行（输入 + 按钮）

- 布局：`row`，`justify-content: space-between`，`align-items: center`，`gap: 12px`，`padding: 0 6px 0 14px`，`min-width: 0`。
- 输入区：`flex: 1 1 0%`，`min-width: 0`，填满除按钮外的空间；单行，不折行；超出时前面遮罩，尾部跟随（通过 scrollLeft 实现）。
- 右侧按钮：`flex-shrink: 0`，不参与收缩。

## 分割线

- 宽度 100%，高度 0，`border-bottom: 1px solid #F5F7F9`。

## 建议区（列表 + 文本）

- 容器：`column`，`align-self: stretch`，`gap: 14px`，`padding: 14px 8px`。
- 列表区：`column`，`gap: 8px`，`width: 100%`。
- 文本区：`column`，`gap: 12px`，`padding: 0 0 0 8px`，`width: 100%`。

## 列表/文本项

- 列表项与文本项均**填满容器宽度**，无固定宽度；单行，不折行，超出以「...」省略。
