# 组件规范

## Button_A（安装按钮，列表右侧）

| 状态 | 背景 | 文字 | 圆角 |
|------|------|------|------|
| 默认 | `#000000` | `#FFFFFF` | 100px |
| Hover | `#333333` | `#FFFFFF` | 100px |
| Variant2 | `#000000` | `#333333` | 100px |

- 布局：`row`，`justify-content: center`，`align-items: center`，`gap: 10px`，`padding: 4px 12px`。
- 字体：Microsoft YaHei，12px，Regular，行高约 1.32。

## Button2（AI搜索，搜索框右侧）

- 背景：`#F5F7F9`，Hover：`#EFF1F6`，圆角 100px。
- 内容：icon 14×14 + 文案「AI搜索」，字体 10px。
- 布局：`row`，`align-items: center`，`gap: 1px`，`padding: 4px 6px`。

## 搜索列表（List 卡片）

- 容器：背景 `#F5F7F9`，Hover `#EFF1F6`，圆角 8px，`padding: 12px`，`gap: 91px`（左侧内容与右侧按钮之间）。
- 左侧内容：图标 30×30（圆角 6px）+ 文本区（标题 14px Bold，副标题 12px 颜色 `#666666`），`gap: 8px`。
- 文本区：单行，超出省略（`white-space: nowrap`，`text-overflow: ellipsis`），最大宽度不超出容器。

## 搜索文本（Text 建议行）

- 布局：`row`，`align-items: center`，`gap: 4px`。
- 内容：图标 14×14 + 文案，字体 14px Regular。
- 单行，超出省略，最大宽度不超出容器。

## 图标

- **icon/搜索**：14×14，描边 `#333333` 或 `currentColor`。
- **icon/AI搜索**：14×14，含线性渐变（#3AA7FF → #966EFF → #FF9584）与实色部分。
